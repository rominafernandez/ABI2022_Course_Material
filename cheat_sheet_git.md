# Git Cheat-Sheet

| Command                                       | Explanation |
| ----                                          | ----  |
| **SETUP**                                     |       |
| `git config --global user.name "[name]" `     | Set global name for user |
| `git config --global user.email "[E-Mail]"`   | Set global E-Mail for user |
| **SETUP & INT**                               |       |
| `git init`                                    | Initializes an existing directory as git repository |
| `git clone [url]`                             | Clones remote repository to local repository |
| **STAGE & SNAPSHOT**                          |       |
| `git status`                                  | Shows modified files in working directory, staged for next commit |
| `git add [file]`                              | Adds files from local repository to staging area |
| `git reset [file]`                            | Unstages a file while retaining the changes in the working directory |
| `git diff`                                    | Shows difference of what is changed but not staged |
| `git diff --staged`                           | Shows difference of what is staged but not yet comitted |
| `git commit -m "[descriptive message]"`       | Commits files from staging area to local repository with explanatory message |
| **BRANCH & MERGE**                            |       |
| `git branch`                                  | Lists all branches. A * appears next to the currently active branch |
| `git branch [branch-name]`                    | Creates a new branch at the current commit |
| `git checkout [branch-name]`                  | Switches to another branch and checks it out into working directory |
| `git checkout [commit-id]`                    | Switches to chosen commit (HEAD points to other commit) |
| `git merge [branch-name]`                     | Merges named branch's history into current branch. Opens editor |
| `git log`                                     | Shows all commits in current branch's history |
| `git switch -c`                               | Creates new branch (alternate timeline to earlier commit) |
|**TRACKING PATH CHANGES**                      |       |
| `git rm [file]`                               | Deletes file from project and stage the removal for commit |
| `git mv [existing-path][new-path]`            | Changes existing file path and stages the mobe. Can also be used for renaming |
| **SHARE & UPDATE**                            |       |
| `git push`                                    | Pushes local repository to remote repository |
| `git remote set-url origin [url]`             | E.g. after renaming a repository to set the local repository to the new URL. |
| `git push-u origin master`                    | Pishes the commits in the local branch named master to the remote named origin| 
