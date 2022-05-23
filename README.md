# git-commands
This repo will list the important git commands.

git diff--- difference between files

git add -p <filename> lets us stage only specific parts of files instead of complete files.

git log will show the history of our commits.

**Branching Strategies** 
State, features and Release branches

Long-lived branches: master or main branches
no direct commits to long-lived branches, only to short-lived branches.

Short-lived branches: deleted after they are integrated (merge/rebase).

**Pull requests**
Lets the team review the code.

A fork is your personal copy of a git repository.

git branch <branch-name> creates a new branch.

**Merge Conflicts**
git merge <branch-name> will merge the branch to your current working (checkout) branch.

git merge --abort will abort the current merge and return to the state before merge.

merge commit is created automatically by git.

**Rebase**
Rebase is not better than merge, it is just different.
git rebase <branchname> will rebase specifed branch with the current checkout branch.
Rebase should be used for cleaning up your local repository.
Rebase re-writes commit history.


