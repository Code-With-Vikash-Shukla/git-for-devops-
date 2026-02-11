clear
Clears the terminal screen.

pwd
Shows the present working directory.

ls
Lists files and directories.

ls -a
Shows all files including hidden ones.

ls -l
Displays detailed file information.

mkdir project-name
Creates a new directory.

cd project-name
Moves into a directory.

touch file.txt
Creates an empty file.

rm file.txt
Deletes a file permanently.

cat file.txt
Displays file content.

vim file.txt
Opens a file for editing.

Git Installation & Verification
git
Checks if Git is installed.

git --version
Shows the installed Git version.

Initialize a Git Repository
git init
Initializes a new Git repository by creating a .git folder.

Checking Repository Status
git status
Shows the current state of the working directory and staging area.

Configuring Git User Information
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
Sets your identity for commits.

Git Workflow
Working Directory → Staging Area → Repository

Tracking Files (Staging Area)
git add file.txt
Stages a specific file.

git add .
Stages all modified files.

git rm --cached file.txt
Unstages a file without deleting it.

Committing Changes
git commit -m "commit message"
Saves staged changes with a message.

git commit -a -m "commit message"
Stages and commits tracked files in one step.

Viewing Commit History
git log
Displays detailed commit history.

git log --oneline
Displays a short commit history.

Restoring Files
git restore file.txt
Reverts a file to its last committed state.

Removing Files
rm file.txt
Deletes a file from the directory.

git rm file.txt
Deletes and stages the file removal.

Working with Branches
git branch
Lists all branches.

git branch dev
Creates a new branch.

git checkout dev
Switches to another branch.

git checkout -b dev
Creates and switches to a branch.

git switch dev
Switches branches (modern command).

Viewing Repository Structure
tree
Shows project structure in tree format.

Installing Tree Command (Linux)
sudo apt install tree
Installs the tree command.

Viewing Terminal History
history
Shows previously used commands.

Common Mistakes to Avoid
Incorrect commands:

git staus
git comit
gti branch
Correct commands:

git status
git commit
git branch
git pull origin main 



