# vscode101
About Visual Studio Code

# setup Git
git --version<br>
git config --global user.name "name"<br>
git config --global user.email "email"<br>
git config --list

# using Git in VS Code
git init<br>
git add .<br>
git commit -m "commit message"<br>
git remote add origin {repository url}<br>
git push -u origin master

# fixed merge conflicts
git pull origin main --rebase<br>
git add .<br>
git commit -m "Fixed merge conflicts"<br>
git push origin main

# reset the local changes to match the remote
git reset --hard origin/main<br>
git push origin main
