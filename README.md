# Programming Zero To Hero

A collection of **50 beginner-friendly programming problems** designed to help new developers go from zero to hero. Problems are **language-agnostic** — pick any programming language you like (Python, Java, C++, JavaScript, Go, Rust, …) and submit your solution.

## Who Is This For?
- Students learning their first programming language.
- Developers switching to a new language who want warm-up exercises.
- Anyone who wants to practice fundamentals: variables, loops, conditionals, strings, arrays, basic math, patterns.

## Repository Structure
```
.
├── README.md                  <- you are here
├── CONTRIBUTING.md            <- full contribution guide (PR workflow)
├── CODE_OF_CONDUCT.md         <- community standards
├── Basic_Programming/         <- one markdown file per problem (Q01 … Q50)
└── solutions/                 <- contributor solutions grouped by problem
    └── Q01-hello-world/
        ├── python/
        │   ├── solution.py
        │   └── README.md
        └── java/
            ├── Solution.java
            └── README.md
```

## Before You Contribute
Please read these two files first:
- 📄 [CONTRIBUTING.md](./CONTRIBUTING.md) — step-by-step guide to raising a Pull Request, branch naming, folder structure, and the PR template.
- 🤝 [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) — how we expect contributors and reviewers to treat each other.

## How Issues Work
Each of the 50 problems has a corresponding **GitHub issue** with the full statement, example input/output, and acceptance criteria. The issue is the single source of truth — pick one, claim it, and solve it.

## Contribution Workflow
1. **Pick a problem.** Browse the list below and open the issue you want to solve.
2. **Claim it.** Leave a comment on the issue like `I'd like to work on this in <language>`. The maintainer will assign it to you.
3. **Fork & branch.** Fork this repo, then create a branch named after the problem and language, e.g. `q07-simple-interest-python`.
4. **Add your solution.** Place it under `solutions/Q<nn>-<slug>/<language>/` as described in each issue. Include a small `README.md` with how to run it.
5. **Open a Pull Request.** Reference the issue in your PR description using `Closes #<issue-number>` so it auto-closes on merge.
6. **Code review.** The maintainer will review your PR, request changes if needed, and merge once it meets the acceptance criteria.

## Pull Request Checklist
Before you request a review, make sure:
- [ ] Your code compiles / runs with no errors.
- [ ] It reads input and prints output **exactly** as the issue specifies.
- [ ] Files live in the correct folder: `solutions/Q<nn>-<slug>/<language>/`.
- [ ] A `README.md` in your solution folder explains how to run it.
- [ ] The PR title is descriptive, e.g. `Q07: Simple Interest in Python`.
- [ ] The PR body contains `Closes #<issue-number>`.

## Multiple Solutions Welcome
More than one person can solve the same problem — just use a different language folder. Two Python solutions for the same problem should go into separate folders if they take different approaches (e.g. `python-iterative/`, `python-recursive/`).

## Rules of Engagement
- Be respectful in comments and reviews.
- Don't copy-paste from other contributors' PRs.
- Keep solutions readable — this repo is for learners.
- One PR per issue (don't bundle multiple problems in a single PR).

## The 50 Problems

| #  | Problem |
|----|---------|
| 01 | [Hello World](Basic_Programming/Q01-hello-world.md) |
| 02 | [Sum of Two Numbers](Basic_Programming/Q02-sum-of-two-numbers.md) |
| 03 | [Even or Odd](Basic_Programming/Q03-even-or-odd.md) |
| 04 | [Maximum of Three Numbers](Basic_Programming/Q04-max-of-three.md) |
| 05 | [Area of a Rectangle](Basic_Programming/Q05-area-of-rectangle.md) |
| 06 | [Celsius to Fahrenheit](Basic_Programming/Q06-celsius-to-fahrenheit.md) |
| 07 | [Simple Interest](Basic_Programming/Q07-simple-interest.md) |
| 08 | [Swap Two Variables](Basic_Programming/Q08-swap-two-variables.md) |
| 09 | [Check Leap Year](Basic_Programming/Q09-leap-year.md) |
| 10 | [Positive, Negative or Zero](Basic_Programming/Q10-positive-negative-zero.md) |
| 11 | [Print 1 to N](Basic_Programming/Q11-print-1-to-n.md) |
| 12 | [Sum of First N Natural Numbers](Basic_Programming/Q12-sum-1-to-n.md) |
| 13 | [Factorial of a Number](Basic_Programming/Q13-factorial.md) |
| 14 | [Multiplication Table](Basic_Programming/Q14-multiplication-table.md) |
| 15 | [Fibonacci Series](Basic_Programming/Q15-fibonacci-series.md) |
| 16 | [Count Digits in a Number](Basic_Programming/Q16-count-digits.md) |
| 17 | [Reverse a Number](Basic_Programming/Q17-reverse-number.md) |
| 18 | [Sum of Digits](Basic_Programming/Q18-sum-of-digits.md) |
| 19 | [Palindrome Number](Basic_Programming/Q19-palindrome-number.md) |
| 20 | [Prime Number Check](Basic_Programming/Q20-prime-number.md) |
| 21 | [Reverse a String](Basic_Programming/Q21-reverse-string.md) |
| 22 | [Count Vowels and Consonants](Basic_Programming/Q22-count-vowels-consonants.md) |
| 23 | [String Palindrome](Basic_Programming/Q23-string-palindrome.md) |
| 24 | [Count Words in a Sentence](Basic_Programming/Q24-count-words.md) |
| 25 | [Convert Case](Basic_Programming/Q25-uppercase-lowercase.md) |
| 26 | [Anagram Check](Basic_Programming/Q26-anagram-check.md) |
| 27 | [Remove Duplicate Characters](Basic_Programming/Q27-remove-duplicate-chars.md) |
| 28 | [Longest Word in a Sentence](Basic_Programming/Q28-longest-word.md) |
| 29 | [Replace a Character](Basic_Programming/Q29-replace-character.md) |
| 30 | [Count Character Occurrences](Basic_Programming/Q30-count-character-occurrences.md) |
| 31 | [Maximum Element in an Array](Basic_Programming/Q31-array-max.md) |
| 32 | [Minimum Element in an Array](Basic_Programming/Q32-array-min.md) |
| 33 | [Sum of Array Elements](Basic_Programming/Q33-array-sum.md) |
| 34 | [Average of an Array](Basic_Programming/Q34-array-average.md) |
| 35 | [Linear Search](Basic_Programming/Q35-linear-search.md) |
| 36 | [Reverse an Array](Basic_Programming/Q36-reverse-array.md) |
| 37 | [Count Even and Odd Numbers](Basic_Programming/Q37-count-even-odd.md) |
| 38 | [Second Largest Element](Basic_Programming/Q38-second-largest.md) |
| 39 | [Remove Duplicates from Array](Basic_Programming/Q39-remove-duplicates-array.md) |
| 40 | [Sort an Array (Ascending)](Basic_Programming/Q40-sort-ascending.md) |
| 41 | [Star Pyramid Pattern](Basic_Programming/Q41-star-pyramid.md) |
| 42 | [Right-Angled Star Triangle](Basic_Programming/Q42-right-triangle.md) |
| 43 | [Greatest Common Divisor](Basic_Programming/Q43-gcd.md) |
| 44 | [Least Common Multiple](Basic_Programming/Q44-lcm.md) |
| 45 | [Armstrong Number](Basic_Programming/Q45-armstrong-number.md) |
| 46 | [Perfect Number](Basic_Programming/Q46-perfect-number.md) |
| 47 | [Binary to Decimal](Basic_Programming/Q47-binary-to-decimal.md) |
| 48 | [Decimal to Binary](Basic_Programming/Q48-decimal-to-binary.md) |
| 49 | [Power of a Number](Basic_Programming/Q49-power.md) |
| 50 | [FizzBuzz](Basic_Programming/Q50-fizzbuzz.md) |

## License
See the [LICENSE](./LICENSE) file in the repository root.

## Maintainer
Review and merge handled by [@Blackvivek](https://github.com/Blackvivek).

---

## 📝 Note

> **This repository is a learning space.** The goal is not perfect, production-grade code — it's **clear, correct, and readable** solutions that help beginners understand programming fundamentals.
>
> - Prefer readability over cleverness. A simple `for` loop is better than an unreadable one-liner.
> - Add a few comments where the logic isn't obvious.
> - Follow the folder structure in [CONTRIBUTING.md](./CONTRIBUTING.md) exactly — it keeps the repo browsable as it grows.
> - Please read the [Code of Conduct](./CODE_OF_CONDUCT.md) before participating.
> - Stuck on something? Start a thread in [GitHub Discussions](../../discussions) — that's where community Q&A lives.

Happy coding! 🚀
