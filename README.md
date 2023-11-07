Init new project for week 2 - task2
## Setting Up the Repository
git init
cd new-project
# Add changes
git add README.md
# Commit changes
git commit -m "init"

# Create and switch to new branch
git checkout -b development

# Add changes
git add .
# Commit changes
git commit -m "commit message"

# Switch to the master branch
git checkout master
# Merge changes from development to master
git merge development
# Push changes to GitHub
git push origin master