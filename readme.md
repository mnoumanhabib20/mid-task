# Git & GitHub Checkpoints & Commands
# start git commands
git init
# remove Origin
git remote remove origin
# Add origin
git remote add origin https://github.com/mnoumanhabib20/mid-task.git
# pull existing files
git pull origin main --allow-unrelated-histories
# add all files to commit
git add .
# Add Commit text
git commit -m "Initial commit"
# push to github repository
git push -u origin main --force


