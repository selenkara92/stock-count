# 2. Require pull requests for changes to main

## Context
Before requiring pull requests, anyone with access could push changes directly to `main` without review. Mistakes or unverified counts could enter the official record unnoticed.

## Decision
Protect the `main` branch and require all changes to go through a branch, a pull request, and a review before merging.

## Consequences
Every change to the stock count is reviewed and documented before becoming official. The trade-off is that simple updates take a few extra steps instead of a direct edit.
