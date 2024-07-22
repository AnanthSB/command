| No. | Command | Description |
|-----|---------|-------------|
| 1   | `ctrl + Alt + B` | Custom shortcut to open Git Bash.|
| 2   | `explorer.exe .` | Open in folder. |
| 3   | `cd` | Open from current directory. |
| 4   | `git config --global user.name "[name]"` | Set a global username. |
| 5   | `git config --global user.email "[email]"` | Set a global email address. |
| 6   | `git config --global color.ui auto` | Enable colorized command line output. |
| 7   | `git init` | Initialize a new Git repository. |
| 8   | `winpty gh auth login` | Authenticate to GitHub. |
| 9   | `gh repo clone ananthsb/mernapp` | Clone the mernapp repository from remote. |
| 10  | `ls` | List out the files/folders of the current directory. |
| 11  | `git status` | Confirm you are up to date and check the branch you are in. |
| 12  | `git add .` | Stage all changes for the next commit. |
| 13  | `git add [file]` | Stage a specific file for the next commit. |
| 14  | `git reset [file]` | Unstage a file while retaining changes in the working directory. |
| 15  | `git commit -m "your commit message"` | Commit staged changes with a message. |
| 16  | `git commit --amend` | Modify the most recent commit. |
| 17  | `git push origin main` | Push changes to the remote repository. |
| 18  | `git push -u origin main` | Push changes and set the upstream branch. |
| 19  | `git checkout -b new-feature-branch` | Create a new branch. |
| 20  | `git checkout existing-branch` | Switch to an existing branch. |
| 21  | `git merge [branch]` | Merge a branch into the current branch. |
| 22  | `git pull origin main` | Pull the latest changes from the remote repository. |
| 23  | `gh pr create --base main --head new-feature-branch --title "Title of PR" --body "Description of PR"` | Create a pull request. |
| 24  | `npm install` | Install dependencies. |
| 25  | `npm run server (backend)` | Run server (backend). |
| 26  | `npm start (frontend)` | Start application (frontend). |
| 27  | `cat filename` | Print file content. |
| 28  | `git log --oneline` | Show commit history in one line per commit. |
| 29  | `git log` | Show all commits in the current branch’s history. |
| 30  | `git log branchB..branchA` | Show the commits on branchA that are not on branchB. |
| 31  | `git log --follow [file]` | Show the commits that changed file, even across renames. |
| 32  | `git log --stat -M` | Show all commit logs with an indication of any paths that moved. |
| 33  | `git diff` | Show changes between working directory and index. |
| 34  | `git diff --staged` | Show changes between index and HEAD. |
| 35  | `git diff main...dev` | Compare changes between branches. |
| 36  | `git branch` | List local branches. |
| 37  | `git branch -r` | List remote branches. |
| 38  | `git branch -a` | List all local and remote branches. |
| 39  | `git remote -v` | Show remote repositories. |
| 40  | `git fetch origin` | Fetch changes from the remote repository. |
| 41  | `git rebase [branch]` | Reapply commits on top of another base tip. |
| 42  | `git stash` | Stash changes in a dirty working directory. |
| 43  | `git stash list` | List stack-order of stashed file changes. |
| 44  | `git stash pop` | Apply the top stash and remove it from the stack. |
| 45  | `git stash drop` | Remove a single stash from the stack. |
| 46  | `git config --list` | List all usernames and email addresses. |
| 47  | `q (exit)` | Exit from a Git command output (less pager). |
