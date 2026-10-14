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
├── questions/                 <- one markdown file per problem (Q01 … Q50)
└── solutions/                 <- contributor solutions grouped by problem
    └── Q01-hello-world/
        ├── python/
        │   ├── solution.py
        │   └── README.md
        └── java/
            ├── Solution.java
            └── README.md
```

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
| 01 | [Hello World](questions/Q01-hello-world.md) |
| 02 | [Sum of Two Numbers](questions/Q02-sum-of-two-numbers.md) |
| 03 | [Even or Odd](questions/Q03-even-or-odd.md) |
| 04 | [Maximum of Three Numbers](questions/Q04-max-of-three.md) |
| 05 | [Area of a Rectangle](questions/Q05-area-of-rectangle.md) |
| 06 | [Celsius to Fahrenheit](questions/Q06-celsius-to-fahrenheit.md) |
| 07 | [Simple Interest](questions/Q07-simple-interest.md) |
| 08 | [Swap Two Variables](questions/Q08-swap-two-variables.md) |
| 09 | [Check Leap Year](questions/Q09-leap-year.md) |
| 10 | [Positive, Negative or Zero](questions/Q10-positive-negative-zero.md) |
| 11 | [Print 1 to N](questions/Q11-print-1-to-n.md) |
| 12 | [Sum of First N Natural Numbers](questions/Q12-sum-1-to-n.md) |
| 13 | [Factorial of a Number](questions/Q13-factorial.md) |
| 14 | [Multiplication Table](questions/Q14-multiplication-table.md) |
| 15 | [Fibonacci Series](questions/Q15-fibonacci-series.md) |
| 16 | [Count Digits in a Number](questions/Q16-count-digits.md) |
| 17 | [Reverse a Number](questions/Q17-reverse-number.md) |
| 18 | [Sum of Digits](questions/Q18-sum-of-digits.md) |
| 19 | [Palindrome Number](questions/Q19-palindrome-number.md) |
| 20 | [Prime Number Check](questions/Q20-prime-number.md) |
| 21 | [Reverse a String](questions/Q21-reverse-string.md) |
| 22 | [Count Vowels and Consonants](questions/Q22-count-vowels-consonants.md) |
| 23 | [String Palindrome](questions/Q23-string-palindrome.md) |
| 24 | [Count Words in a Sentence](questions/Q24-count-words.md) |
| 25 | [Convert Case](questions/Q25-uppercase-lowercase.md) |
| 26 | [Anagram Check](questions/Q26-anagram-check.md) |
| 27 | [Remove Duplicate Characters](questions/Q27-remove-duplicate-chars.md) |
| 28 | [Longest Word in a Sentence](questions/Q28-longest-word.md) |
| 29 | [Replace a Character](questions/Q29-replace-character.md) |
| 30 | [Count Character Occurrences](questions/Q30-count-character-occurrences.md) |
| 31 | [Maximum Element in an Array](questions/Q31-array-max.md) |
| 32 | [Minimum Element in an Array](questions/Q32-array-min.md) |
| 33 | [Sum of Array Elements](questions/Q33-array-sum.md) |
| 34 | [Average of an Array](questions/Q34-array-average.md) |
| 35 | [Linear Search](questions/Q35-linear-search.md) |
| 36 | [Reverse an Array](questions/Q36-reverse-array.md) |
| 37 | [Count Even and Odd Numbers](questions/Q37-count-even-odd.md) |
| 38 | [Second Largest Element](questions/Q38-second-largest.md) |
| 39 | [Remove Duplicates from Array](questions/Q39-remove-duplicates-array.md) |
| 40 | [Sort an Array (Ascending)](questions/Q40-sort-ascending.md) |
| 41 | [Star Pyramid Pattern](questions/Q41-star-pyramid.md) |
| 42 | [Right-Angled Star Triangle](questions/Q42-right-triangle.md) |
| 43 | [Greatest Common Divisor](questions/Q43-gcd.md) |
| 44 | [Least Common Multiple](questions/Q44-lcm.md) |
| 45 | [Armstrong Number](questions/Q45-armstrong-number.md) |
| 46 | [Perfect Number](questions/Q46-perfect-number.md) |
| 47 | [Binary to Decimal](questions/Q47-binary-to-decimal.md) |
| 48 | [Decimal to Binary](questions/Q48-decimal-to-binary.md) |
| 49 | [Power of a Number](questions/Q49-power.md) |
| 50 | [FizzBuzz](questions/Q50-fizzbuzz.md) |

## License
MIT — see `LICENSE` once added.

## Maintainer
Review and merge handled by the repository owner.
