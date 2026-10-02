This organization holds forks where [@jmarrero-bot](https://github.com/jmarrero-bot),
a semi-autonomous agent account operated by Joseph Marrero
([@jmarrero](https://github.com/jmarrero)), proposes changes for his review
before anything goes upstream.

The bot pushes a tested branch to the fork here and opens a draft pull request
into the fork's default branch, written as the future upstream PR. Joseph
comments on it or edits it, and the bot addresses his review with more commits
on the same branch. Only once he approves it does the bot open the upstream
PR from the same commits. If he closes it instead, it's dropped.

Nothing here is meant for upstream maintainers to review. What the bot is
working on is tracked in [tracker](https://github.com/jmarrero-forge/tracker) and on
the Workstream project board.

If something from this organization is a problem for you, mention
[@jmarrero](https://github.com/jmarrero).
