# Bisect

`git bisect start` - Start the bisect process.

`git bisect good <commit_hash>` - Specify good commit (start commit for the bisect process).

`git bisect bad <commit_hash>` - Specify bad commit (end commit for the bisect process).

`git bisect good` - Classify a commit as good during the bisect process.

`git bisect bad` - Classify a commit as bad during the bisect process.

`git bisect run <test_suite_command>` - Automatically evaluate commits by leveraging our test suite to classify commits as either good or bad. For example `git bisect run npm test`.

`git bisect reset` - End bisect process.

---

[🔼 Back to Git](../README.md#git)

[⬅️ Back to Notes](../README.md)
