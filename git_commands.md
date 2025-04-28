| Category        | Command                                     | Description                                  |
|-----------------|---------------------------------------------|----------------------------------------------|
| Setup           | git config --global user.name "Name"        | Set Git username globally                    |
| Setup           | git config --global user.email "email"      | Set Git email globally                       |
| Init/Clone      | git init                                    | Initialize a new local repo                  |
| Init/Clone      | git clone <repo-url>                        | Clone a remote repo                          |
| Staging         | git add <file>                              | Stage a specific file                        |
| Staging         | git add .                                   | Stage all changes in current directory       |
| Staging         | git add -A                                  | Stage all (tracked and untracked) changes    |
| Staging         | git add -p                                  | Interactively stage chunks of changes        |
| Committing      | git commit -m "msg"                         | Commit with message                          |
| Committing      | git commit -am "msg"                        | Add + commit tracked files (in one step)     |
| Status/Review   | git status                                  | Show current changes and staging info        |
| Status/Review   | git diff                                    | View unstaged differences                    |
| Status/Review   | git diff --staged                           | View staged changes                          |
| Branching       | git branch                                  | List all local branches                      |
| Branching       | git branch -r                               | List remote branches                         |
| Branching       | git branch -a                               | List all (local + remote) branches           |
| Branching       | git branch -d <branch>                      | Delete a local branch                        |
| Branching       | git checkout -b <new-branch>                | Create and switch to a new branch            |
| Branching       | git switch <branch>                         | Switch to a branch (recommended)             |
| Branching       | git switch -c <new-branch>                  | Create and switch (shortcut)                 |
| Merging         | git merge <branch>                          | Merge another branch into current branch     |
| Log/History     | git log                                     | View commit history                          |
| Log/History     | git log --oneline                           | Compact view of commit history               |
| Log/History     | git log --graph --oneline --all             | Visualize branch history                     |
| Log/History     | git show <commit>                           | Show changes and metadata of a commit        |
| Remote Sync     | git pull                                    | Pull from remote repo                        |
| Remote Sync     | git push                                    | Push to remote repo                          |
| Remote Sync     | git remote -v                               | View remote URLs                             |
| Undo/Reset      | git restore <file>                          | Discard unstaged file changes                |
| Undo/Reset      | git reset <file>                            | Unstage file (keep changes)                  |
| Undo/Reset      | git reset --hard                            | Reset all to last commit (⚠️ destructive)     |
