# swimmeet-privacy

Privacy policy for the SwimMeet iOS app, dated June 13, 2026: a single `index.html` served by GitHub Pages from `main` at `https://benjrohrs.github.io/swimmeet-privacy/`. The comment at the top says it is a styled fragment meant to be pasted into a Squarespace code block. This file is public, like the rest of the repo.

The app's current policy is published from the `stingray-swim-meets` repo instead, and that is the URL the App Store listing uses. Whether anything still links to this page is unknown; ask Ben before changing it or retiring it.

## Git

- Every change goes on its own branch and through a PR. Never push to `main`.
- Merge with `gh pr merge --squash --delete-branch`; no review is needed. There is no CI and no required check. `main` currently has no branch protection, so nothing stops a direct push; follow the rule anyway.
- Merging publishes: GitHub Pages rebuilds from `main` within a few minutes.
- Commands given to Ben go on one line, with no `\` continuations.

## Checks before merging

- No build step. Open `index.html` in a browser and check it renders.
- The policy's source text is kept in the app's own (private) repo; a change here should match it. Say so in the PR description.
- A change to the policy's substance (what data is collected or where it goes) needs Ben's OK.

## What a cloud session can't do

- Change the Squarespace site or the App Store listing: both are Ben's.
- When a cloud session makes a decision worth recording, put it in the PR description so a Mac session can copy it into the docs.
- Never print secret values; check them by length or prefix only.
