# Configuration

`git config --local|--global|--system <section>.<key> <value>` - Configure the specified key-value pair within the specified configuration section (user, core, etc.). `--local` is equivalent to the repo level, `--global` is equivalent to the OS user level, and `--system` is equivalent to the git installation level.

`git config --list` - Show all git configuration values.

`git config --list --show-scope` - Show all git configuration values and the scope (level) where they are defined.

`git config --list --show-origin` - Show all git configuration values and the file where they are defined.

`git config <section>.<key>` - Show the value for the specified configuration section and key.

`git config --local|--global|--system --unset <section>.<key>` - Remove the value for the specified key in the specified section at the specified level.

`git config --local|--global|--system --remove-section <section_name>` - Remove the specified configuration section at the specified level.

`git config --local|--global|--system --edit` - Edit configuration at the specified level (opens up the corresponding configuration file on the default editor).

`git config --global status.submoduleSummary true` - Tell git to show submodule information when running `git status`.

`git config --global diff.submodule log` - Tell git to enable submodule summaries when running diffs.

`git config --global push.recurseSubmodules on-demand` - Automatically push any changes from submodules to the remote when pushing from the parent repo.

`git config --local core.hooksPath .<dir_name>` - Specify a different location within the repo for git to look for hooks (.git directory by default).

---


