# Remotes

`git clone <remote_url>` - Pull the remote repo from the remote URL.

`git remote add <name> <url>` - Track the main branch and HEAD of a hosted repo (remote).

`git remote -v` - Show URLs (fetch and push) for all remotes.

`git fetch` - "Download" changes in the remote branch to our local repo (needs merge as an additional step to integrate changes/resolve conflicts).

`git push` - "Upload" local changes on the current branch to the remote.

`git pull` - Download and merge (fetch + merge) changes in the remote branch in a single step.

`git ls-remote` - List all branches in remote.

`git branch -a` - List all branches (local and remote).

`git fetch origin <remote_branch>` - Fetches the remote branch to local (without creating a local branch; see the following command).

`git checkout --track <remote_branch>` - Set up the local branch to track the remote branch (previously fetched).

---

[🔼 Back to Git](../README.md#git)

[⬅️ Back to Notes](../README.md)
