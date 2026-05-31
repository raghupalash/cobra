# Cobra Contribution Plan

## 1. Understand Cobra's codebase

Start small — Cobra is actually a well-structured, readable codebase:

- Read `command.go` — the heart of the library
- Read `args.go` — simple, good first file
- Look at `*_test.go` files — tests in Go double as documentation

## 2. Find beginner-friendly issues

- [Cobra issues labeled `good first issue`](https://github.com/spf13/cobra/issues?q=is%3Aopen+label%3A%22good+first+issue%22)
- Fix typos/docs first — gets you familiar with the PR process
- Then move to failing tests, then small bug fixes

## 3. Fastest path to first PR (target: 1 week)

1. Complete [A Tour of Go](https://go.dev/tour)
2. Read `args.go` and its tests in the cobra repo
3. Find a [`good first issue`](https://github.com/spf13/cobra/issues?q=is%3Aopen+label%3A%22good+first+issue%22)
4. Submit a fix

## 4. Systems breadth (longer term)

- **[OS: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/)** — free, excellent for understanding OS concepts CLIs rely on (processes, pipes, signals)
- **[The Linux Command Line](https://linuxcommand.org/tlcl.php)** — free book, helps you understand what good CLIs should do
