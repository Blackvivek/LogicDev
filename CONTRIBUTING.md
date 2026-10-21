# Contributing to Programming Zero To Hero

Thank you for taking the time to contribute! This project exists to help new developers practice fundamentals by solving small, well-defined problems in any language they like. Every solution — in any language — is welcome.

Please read this guide before you open your first Pull Request. It covers how to claim an issue, where to put your code, and the exact PR workflow we follow.

---

## 1. Pick an Issue

- Browse the [open issues](../../issues) labelled **`question`** or **`good first issue`**.
- Pick one that looks interesting and is **not already assigned**.
- Leave a comment on the issue like:
  > I'd like to work on this in **Python**.
- The maintainer will assign the issue to you so no one else duplicates the work.

> One issue = one Pull Request. Please don't bundle multiple problems into a single PR.

---

## 2. Fork and Clone

1. Click the **Fork** button at the top-right of the repository page.
2. Clone your fork locally:
   ```bash
   git clone git@github.com:<your-username>/LogicDev.git
   cd LogicDev
   ```
3. Add the original repo as `upstream` so you can keep your fork in sync:
   ```bash
   git remote add upstream git@github.com:Blackvivek/LogicDev.git
   ```

---

## 3. Create a Branch

Use a descriptive branch name that includes the question number and your language:

```bash
git checkout -b q07-simple-interest-python
```

Examples:
- `q01-hello-world-java`
- `q15-fibonacci-cpp`
- `q50-fizzbuzz-javascript`

---

## 4. Add Your Solution

Place your solution under this exact folder structure:

```
solutions/
└── Q<nn>-<slug>/              <- matches the question file name, e.g. Q07-simple-interest
    └── <language>/            <- lowercase: python, java, cpp, javascript, go, rust, …
        ├── solution.<ext>     <- your code (Solution.java, solution.py, etc.)
        └── README.md          <- how to run it
```

### Example

Solving Q07 in Python:

```
solutions/
└── Q07-simple-interest/
    └── python/
        ├── solution.py
        └── README.md
```

### The small `README.md` inside your language folder should include:
- **How to run** your code (compile command, run command).
- **Any dependencies** (language version, libraries).
- **Example run** showing your program handling the sample input.

If multiple people solve the same question in the same language with different approaches, use a suffix on the folder (e.g. `python-iterative/`, `python-recursive/`).

---

## 5. Test Your Code

Before you push, run your program against the **example input** from the issue and confirm the output matches **exactly**. Also try a couple of edge cases (empty input, zero, very large numbers, etc.) — bonus points, not required.

---

## 6. Commit and Push

```bash
git add solutions/Q07-simple-interest/python/
git commit -m "Q07: Simple Interest solution in Python"
git push -u origin q07-simple-interest-python
```

### Commit message style
- Start with the question tag: `Q07:`
- Keep the subject line under 70 characters.
- Use the body (optional) to explain *why*, not *what*.

---

## 7. Open a Pull Request

Go to your fork on GitHub and click **Compare & pull request**.

### PR title
```
Q07: Simple Interest in Python
```

### PR description (template)
```markdown
Closes #<issue-number>

## Summary
Short description of your approach.

## How to run
```bash
python3 solutions/Q07-simple-interest/python/solution.py
```

## Checklist
- [ ] Code compiles / runs without errors
- [ ] Input/output matches the example in the issue
- [ ] Files are under `solutions/Q<nn>-<slug>/<language>/`
- [ ] Added a short README in the solution folder
```

> **Important:** The `Closes #<issue-number>` line is what tells GitHub to auto-close the issue when your PR is merged. Please don't forget it.

---

## 8. Code Review

The maintainer will review your PR within a few days. Possible outcomes:

- ✅ **Approved & merged** — nice work, your name is now in the contributors list.
- 💬 **Changes requested** — the reviewer leaves comments; push new commits to the same branch to address them. No need to open a new PR.
- ❌ **Closed without merging** — only if the PR duplicates another contributor's work or doesn't match the problem. The reviewer will explain why.

Please be patient and respond to review comments. Good contributions take a short conversation, not just a single push.

---

## Pull Request Checklist (TL;DR)

Before you request a review, make sure all of these are true:

- [ ] Your code compiles / runs with no errors.
- [ ] It reads input and prints output **exactly** as the issue specifies.
- [ ] Files live under `solutions/Q<nn>-<slug>/<language>/`.
- [ ] A `README.md` in your solution folder explains how to run it.
- [ ] The PR title is descriptive, e.g. `Q07: Simple Interest in Python`.
- [ ] The PR body contains `Closes #<issue-number>`.
- [ ] You've read the [Code of Conduct](./CODE_OF_CONDUCT.md).

---

## What Happens If I Get Stuck?

Totally fine — this project is for learners. You have a few options:

1. **Comment on the issue** you're working on with your question.
2. **Start a thread in [GitHub Discussions](../../discussions)** — the best place for general help, approach questions, and community Q&A.
3. **Open a new issue** with the label `help wanted` only if you've found a real bug or something that needs tracking.

Don't just abandon the branch silently — leave a comment so the issue can be reassigned to someone else.

---

## Note

> This repository is a **learning space**. The goal is not perfect, production-grade code — it's clear, correct, readable solutions that help beginners understand programming fundamentals. Comments, meaningful variable names, and small README explanations are more valuable than one-line clever tricks.

Thank you for contributing. 🚀
