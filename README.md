# kottans-frontend

As I already know basics, I'll include here some new things that I learned 

## Git intro
### I learned that:
* We can use `git log --oneline` to see only hash and commit
* `git log --stat` shows the number of insertions and deletions in a file
* `git log -p` or `--patch` displays actual changes to the file
* The `git show` command will show only one commit
* Flag `-w` ignores whitespaces 
* We can create a new branch from a commit using `git branch <name> hash`
* The `--decorate` flag makes git log display all of the references (e.g., branches, tags, etc) that point to each commit
* The `--graph` flag adds the bullets and lines to the leftmost part of the output
* The `--all` flag is what displays all of the branches in the repository
* `git merge <other-branch>` is used to merge a branch into a master
* `git revert <SHA-of-commit-to-revert>` to revert a commit
* `git reset` leaves changes in the working directory, `git reset soft` leaves them in staging index, `git reset hard` deletes them

<details>
  <summary>VCS with Git</summary>
  <img src ="screenshots/git1.png">
</details>
<details>
  <summary>Main</summary>
  <img src ="screenshots/git3.png" width=95%>
</details>
<details>
  <summary>Remote</summary>
  <img src ="screenshots/git4.png" width=95%>
</details>

## Linux CLI, and HTTP
### I learned that:
* We can use ls -l to display detailed ls
* We can give different permissions to files using  chmod to add permissions to groups or users
* We can use ~ instead of home dir
* We use `find <directory> name <filename>` to look for files
* We use `cat` to concatinate files
* We use `lpr, lpq, lprm` for printer
* `df` shows space left on the computer
* `-r ` stands for recursive and can be used for copying or removing files
* We use `ps aux` to see all the processes
<details>
  <summary>Linux</summary>
  <img src ="screenshots/linux.png">
</details>

## Git Collaboration
### I learned:
* What means forking the repository and how it works on github
* It's possible to add all the files in the directory to the commit using git add .
* To create a new branch we need to use `git push origin <branchname>`
* Git `shortlog` command
* We can use `git log --author=` to specify the author
* We can use `git log --grep=` for looking for commints by words
* There exist a `CONTRIBUTING.md`  file 
* It's possible to star a repository or to watch it on github
* It's possible to use `git remote add upstream` and use with forked project
* It's possible to rename origin with `git remote rename <name> origin`
* We can use `git rebase` to squash commits together
