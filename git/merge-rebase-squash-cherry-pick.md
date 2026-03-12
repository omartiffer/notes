# Merge, Rebase, Squash, and Cherry-picking

`git merge <branch_name>` - Merge all commits **FROM** the specified branch **TO** the current branch.

`git merge --abort` - Stop merge and return the working tree to the previous state (before merge started).

`git merge-base <branch1> <branch2>` - Determine the best common ancestor for a rebase.

`git rebase <branch_name>` - Rebase current branch commits **ON** the specified branch.

`git rebase <commit_hash>` - Rebase current branch commits **ON** the specified commit.

`git rebase -i <branch_name>|<commit_hash>` - Same as previous two, but interactive.

`git cherry-pick <commit_hash>` - Copy the specified commit and append it to the HEAD of the current branch.

---

[🔼 Back to Git](../README.md#git)

[⬅️ Back to Notes](../README.md)
