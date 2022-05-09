# git-practice2

Hello. We're practicing git.

## Merging upstream changes

### Basic use case

If you're working on a branch (you should be!!),
you would commit your changes. 

Then, switch to the `main` branch.

`git pull` should bring down any branch references *and*, more importantly, the latest code changes on `main`.

Next, you switch back to your personal branch using
`git switch <branch>` or `git checkout <branch>`.

Finally, you merge changes using `git merge main` (ie the name of the branch you're trying to *merge into the currently checkout branch*.
