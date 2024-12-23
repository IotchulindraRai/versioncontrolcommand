# version control command
It is a basic git version command required to push code in github
# Initialize Git repository (if not done previously)
git init

# Check the status of your repository
git status

# Add changes to the staging area
git add .

# Commit the changes with a commit message
git commit -m "Your commit message here"

# Add a remote repository (if not done previously)
# Note: This command is optional if you've already added the remote
git remote add origin https://github.com/IotchulindraRai/Javascript-interview-.git

# Verify the remote
git remote -v

# Push changes to the remote repository
git push -u origin main
![01MjNCWMrwj_Gkfrj](https://github.com/IotchulindraRai/versioncontrolcommand/assets/87846923/9a886e86-c0ce-41ec-b8fc-23f85cb4e282)

# moreover Certainly! Here are 20 Git commands that are commonly used by software engineers:

# Initialize a new repository:

git init
# Clone a repository:

git clone <repository_url>
# Check the status of your repository:

git status
# Add changes to the staging area:

git add <file_name>
# Add all changes to the staging area:

git add .
# Commit changes:

git commit -m "Your commit message here"
# View the commit history:

git log
# Create a new branch:

git branch <branch_name>
# Switch to a different branch:

git checkout <branch_name>
# Create and switch to a new branch:

git checkout -b <new_branch_name>
# Merge branches:

git merge <branch_name>
# Fetch changes from a remote repository:


git fetch
# Pull changes from a remote repository:

git pull
# Push changes to a remote repository:

git push origin <branch_name>
# Undo changes in working directory:

git restore <file_name>
# Discard changes in the working directory:

git checkout -- <file_name>
# Create a tag for a specific commit:

git tag -a <tag_name> -m "Your tag message" <commit_hash>
# List all tags:

git tag
# Show changes between commits:

git diff <commit_hash_1> <commit_hash_2>
 # Remove untracked files:

git clean -fd
These commands cover a range of Git operations that are commonly used in software development workflows. Remember to adapt these commands based on your specific use case and workflow.





