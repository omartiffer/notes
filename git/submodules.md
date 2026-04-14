# Submodules

`git submodule add <remote_url> <local_path>` - Add remote repo as a submodule under the specified local path (directory).

`git submodule init` - Use after cloning a repo that has submodules to integrate with the config of your local repo.

`git submodule update` - Use after init to grab the content of the reference for the specific commit of the submodules.

`git submodule deinit <local_path>` - Temporarily remove the submodule at the local path (directory). It can be initialized again.

To permanently remove a submodule, use the following sequence of commands:

```bash
git submodule deinit <local_path>
git rm <local_path>
git commit -m "Commit message"
```

`git clone --recursive <remote_url> <local_repo_name>` - Clone repo with all tree of submodules, initialize, and update them.

`git submodule foreach '<command>'` - Execute command for each submodule in the repo. For example `git submodule foreach 'cat .gitmodules'`.

`git submodule sync --recursive` - Sync for remote changes in submodules.

`git submodule update --init --recursive` - Init and update all submodules in the tree after syncing.

---


