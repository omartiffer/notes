# Commit History

`git log` - Provide a view of the commit history.

`git log --oneline` - Show commit history (one line per commit).

`git log --graph` - Show a visual representation of the commit history.

`git log --stat` - Provide additional info on what files were changed in each commit.

`git log --patch` - Provide additional info on the specific changes committed.

`git log <branch_name>` - Show commit history for the specified branch.

`git commit --amend` - Modify the latest commit in the history.

`git reset --soft <commit_hash>` - Reset HEAD to the specified commit without touching the staging area or working tree.

`git reset --mixed <commit_hash>` - Default behavior. Same as previous, but only keeps the working tree.

`git reset --hard <commit_hash>` - Discard all commits from the specified commit up to the last commit.

`git reflog` - Show a history of where HEAD has been, effectively keeping track of all operations on the commit history. It can be used with `git reset` or `git cherry-pick` to "recover" a discarded commit.

---


