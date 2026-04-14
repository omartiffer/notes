# Plumbing Commands

`git hash-object --stdin` - Generate a SHA1 hash for the text passed from STDIN and print it to STDOUT.

`git hash-object -w --stdin` - Generate hash for the content passed from STDIN and save it as a **blob** to the repo.

`git cat-file -t <hash>` - Print the saved object's type for the provided hash.

`git cat-file -p <hash>` - Print the saved object's contents.

`git count-objects` - Count the number of objects in Git's object database.

`git show-ref <branch_name>` - List all tracked branches that have the specified branch name in their names.

---


