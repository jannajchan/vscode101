# vscode101
About Visual Studio Code

# setup Git
git --version
git config --global user.name "name"
git config --global user.email "email"
git config --list

# using Git in VS Code
git init
git add .
git commit -m "commit message"
git remote add origin {repository url}
git push -u origin master

# fixed merge conflicts
git pull origin main --rebase
git add .
git commit -m "Fixed merge conflicts"
git push origin main

# reset the local changes to match the remote
git reset --hard origin/main
git push origin main
