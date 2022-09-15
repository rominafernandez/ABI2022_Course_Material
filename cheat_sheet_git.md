# Git Cheat-Sheet

| Command                       | Explanation |
| ----                          | :---- |
| **SETUP**                     |       |
| `git config --global user.name "[name]" ` | Set global name for user |
| `git config --global user.email "[E-Mail]"` | Set global E-Mail for user |
| **SETUP & INT**               |           |
| `git init`                    | Initializes an existing directory as git repository |
| `git clone [url]`             | Clones remote repository to local repository |
| **STAGE & SNAPSHOT**          |           |
| `git status`                    | Shows modified files in working directory, staged for next commit |
| `git add [file]`           | Adds files from local repository to staging area |
| `git reset [file]`        | Unstages a file while retaining the changes in the working directory |
| `git diff`            | Shows difference of what is changed but not staged |
| `git diff --staged`   | Shows difference of what is staged but not yet comitted |
| `git commit -m "[descriptive message]"`       | Commits files from staging area to local repository with explanatory message |
| **BRANCH & MERGE**            |           |
| `git push`                      | Pushes local repository to remote repository |
| `git log`                       | Shows all commits in terminal |
| `git checkout commit-id`        | Switches to chosen commit (HEAD points to other commit) |
| `git checkout branchname`       | Instead of commit-id one can use branch names |
| `git switch -c`                 | Creates new branch (alternate timeline to earlier commit) |
| `git push -u origin branchname` | Pushes new branch to github |
| `git merge branchname`          | Merges named branch into other branch (master). Opens editor |
