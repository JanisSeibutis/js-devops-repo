# Branching strategy

## Chosen strategy

Conventional branch names are to be used.

## Branch protection

With team i would form rules so that main cannot be deleted and so that any pullrequest requires atleast 1 review.

## Tagging and versioning

v0.1.0 is the first tagged version. The repo has a branching strategy, a pull request template and a CODEOWNERS file, but no application yet. The 0 in front means everything can still change. The next version number follows from the commit messages: a fix: gives v0.1.1, a feat: gives v0.2.0, and a docs: change does not change the version at all.
