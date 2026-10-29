# Git Practice Log

## Git Commands Used and Purpose
- git init -b main: Initializes a local Git repository with the main branch.
- git remote add origin <url>: Links the local repository to GitHub.
- git status: Checks the status of staged and unstaged files.
- git add <file>: Stages modifications for commit.
- git commit -m "<message>": Saves staged changes with a commit message.
- git branch <name>: Creates a new branch.
- git checkout -b <name>: Creates and switches to a new branch.
- git merge <name>: Combines changes from another branch into the active branch.
- git push -u origin <name>: Pushes branch commits to the remote GitHub repository.
- git pull origin <name>: Fetches and integrates changes from GitHub to the local branch.

## Merge Conflict Description & Resolution
- Scenario: A merge conflict occurred while integrating feature/exercise-update into main where README.md was modified on the same line.
- Resolution: Inspected the file, identified the conflicting markers (<<<<<<<, =======, >>>>>>>), edited the file manually to keep the desired version, removed the markers, staged the resolved file using git add README.md, and ran git commit to complete the merge.# Git Commands & Practice Log

## Commands Used
- `git init -b main`: Initializes a new Git repository with `main` as the default branch.
- `git remote add origin <url>`: Links the local repository to the remote GitHub repository.
- `git status`: Checks the state of the working directory and staging area.
- `git add <file>`: Stages changes for the next commit.
- `git commit -m "<message>"`: Records staged snapshots to the repository history.
- `git branch <branch-name>`: Creates a new branch.
- `git checkout -b <branch-name>`: Creates and switches to a new branch.
- `git merge <branch-name>`: Joins two development histories together.
- `git push -u origin <branch-name>`: Pushes commits to the remote repository and sets upstream tracking.
- `git pull`: Fetches and integrates changes from the remote repository.

## Merge Conflict Scenario & Resolution
- **Encountered**: A conflict occurred when merging a feature branch into `main` where the same line in `README.md` was edited concurrently on both branches.
- **Resolution**: Opened `README.md`, located the conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`), kept the intended final text, removed the conflict markers, staged the resolved file using `git add README.md`, and completed the merge with `git commit`.
