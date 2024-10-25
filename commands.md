Git Commands Cheat Sheet
Basic Commands
Initialize a repository:
git init

Clone a repository:
git clone <repository-url>

Check status:
git status

List files:
ls (Unix) / dir (Windows)

Configuration
Set user email:
git config --global user.email "your_email@example.com"

Set user name:
git config --global user.name "Your Name"

List configuration settings:
git config --list

Working with Files
Add a file to staging:
git add <file>

Commit changes:
git commit -m "Your commit message"

Remove a file:
git rm <file>

Restore a staged file:
git restore --staged <file>

View changes:
git diff

Branching
Create a new branch:
git checkout -b <branch-name>

Switch to a branch:
git checkout <branch-name>

List branches:
git branch

Delete a branch:
git branch -d <branch-name>

Merging
Merge a branch into the current branch:
git merge <branch-name>
Remote Repositories
Add a remote repository:
git remote add origin <repository-url>

Push changes to remote:
git push origin <branch-name>

Fetch changes from remote:
git fetch

Pull changes from remote:
git pull origin <branch-name>

Viewing History
Show commit history:
git log

Show a condensed commit history:
git log --oneline

Show changes made in a commit:
git show <commit-hash>

Tags
Create a tag:
git tag <tag-name>

Push tags to remote:
git push origin --tags

Miscellaneous
Undo the last commit (keep changes):
git reset --soft HEAD~1

Undo changes in the working directory:
git checkout -- <file>

View remote repository URLs:
git remote -v
