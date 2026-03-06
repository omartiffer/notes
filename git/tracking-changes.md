# Tracking Changes

`git diff` - Show changes made to files in the working tree since the last commit.

`git diff --staged` or `git diff --cached` - Show staged changes compared to the last commit.

`git diff HEAD` - Show all changes, staged and unstaged.

`git diff -w` - Ignore whitespace from diff.

`git diff <commit_hash>` - Show changes between the specified commit and the current working tree.

`git diff <commit_hash_1>...<commit_hash_2>` - Show changes between commits (uses a common ancestor commit as a starting point if the commits belong to different branches).

`git diff <branch_name_1>...<branch_name_2>` - Show changes between branches starting at a common ancestor commit.

`git show <diff_index_hash>` - Show the original file being compared in diff.

---

[🔼 Back to Git](../README.md#git)

[⬅️ Back to Notes](../README.md)
