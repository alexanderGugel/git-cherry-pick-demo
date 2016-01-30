## git cherry-pick demo

This repo has two branches:
  * `master`
  * `fruits`

`master` is "behind" fruits, which means there are commits on the `fruits` branch that have not been merged into master.

One commit on `fruits` adds an apple script (run it via `node apple.js`).

Your goal is to
  1. Find the commit that added the `apple.js` file.
  2. Create a new branch `apple-cherry`. `apple-cherry` should only have the `cherry.js` and `apple.js` scripts on it.

You are not allowed to copy code between commits.
