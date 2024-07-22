![image](https://github.com/user-attachments/assets/29e83f83-331e-4036-af04-3fcada7af173)



| No.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp; Command | Description |
|-----|---------|-------------|
| 1   | `git config --global user.name "[firstname lastname]"` | Set a name that is identifiable for credit when reviewing version history. |
| 2   | `git config --global user.email "[valid-email]"` | Set an email address that will be associated with each history marker. |
| 3   | `git config --global color.ui auto` | Set automatic command line coloring for Git for easy reviewing. |
| 4   | `git init` | Initialize an existing directory as a Git repository. |
| 5   | `git clone [url]` | Retrieve an entire repository from a hosted location via URL. |
| 6   | `git status` | Show modified files in the working directory, staged for your next commit. |
| 7   | `git add [file]` | Add a file as it looks now to your next commit (stage). |
| 8   | `git reset [file]` | Unstage a file while retaining the changes in the working directory. |
| 9   | `git diff` | Diff of what is changed but not staged. |
| 10  | `git diff --staged` | Diff of what is staged but not yet committed. |
| 11  | `git commit -m "[descriptive message]"` | Commit your staged content as a new commit snapshot. |
| 12  | `git branch` | List your branches. A * will appear next to the currently active branch. |
| 13  | `git branch [branch-name]` | Create a new branch at the current commit. |
| 14  | `git checkout` | Switch to another branch and check it out into your working directory. |
| 15  | `git merge [branch]` | Merge the specified branch’s history into the current one. |
| 16  | `git log` | Show all commits in the current branch’s history. |
| 17  | `git log branchB..branchA` | Show the commits on branchA that are not on branchB. |
| 18  | `git log --follow [file]` | Show the commits that changed file, even across renames. |
| 19  | `git diff branchB...branchA` | Show the diff of what is in branchA that is not in branchB. |
| 20  | `git show [SHA]` | Show any object in Git in human-readable format. |
| 21  | `git rm [file]` | Delete the file from the project and stage the removal for commit. |
| 22  | `git mv [existing-path] [new-path]` | Change an existing file path and stage the move. |
| 23  | `git log --stat -M` | Show all commit logs with an indication of any paths that moved. |
| 24  | `git stash` | Save modified and staged changes. |
| 25  | `git stash list` | List stack-order of stashed file changes. |
| 26  | `git stash pop` | Write working from top of stash stack. |
| 27  | `git stash drop` | Discard the changes from top of stash stack. |
| 28  | `git remote add [alias] [url]` | Add a git URL as an alias. |
| 29  | `git fetch [alias]` | Fetch down all the branches from that Git remote. |
| 30  | `git merge [alias]/[branch]` | Merge a remote branch into your current branch to bring it up to date. |
| 31  | `git push [alias] [branch]` | Transmit local branch commits to the remote repository branch. |
| 32  | `git pull` | Fetch and merge any commits from the tracking remote branch. |
| 33  | `git rebase [branch]` | Apply any commits of the current branch ahead of the specified one. |
| 34  | `git reset --hard [commit]` | Clear staging area, rewrite working tree from specified commit. |
| 35  | `git config --global core.excludesfile [file]` | System-wide ignore pattern for all local repositories. |
