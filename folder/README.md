Instructions for GitHub

# Local to remote repository
git init
git add README.md
git commit -m "README file added"
git branch -M main
git remote add origin https://github.com/znfz/local2remote.git
git push -u origin main

# Clone repository from GitHub to local 
git clone https://github.com/znfz/remote2local.git

# Create a branch locally
git checkout main
git checkout -b branch_1
git add README.md
git commit -m "README file updated for branch_!"
git push origin branch_1

# Create a branch remotely
Use GitHub UI to create branch_2
git fetch --all
git checkout branch_2