# vscode101
About Visual Studio Code


# *** Using GitHub with VS Code ***
# check if Git is installed
git --version

# setup Git
git config --global user.name "name"<br>
git config --global user.email "email"<br>
git config --list
# then signin to GitHub in VS code --> go to "Source Control" (Ctrl + Shift + G)

# initialize Git in project --> open project folder in VS Code then open Terminal (Ctrl + ~)
git init<br>
git remote add origin {repository url} <-- connect to GitHub

# upload code to GitHub
git add . <-- stage all files<br>
git commit -m "commit message" <-- commit changes<br>
git push -u origin main <-- push code to GitHub

# pull updates from GitHub
git pull origin main

# fixed merge conflicts
git pull origin main --rebase<br>
git add .<br>
git commit -m "Fixed merge conflicts"<br>
git push origin main

# remove old remote origin & set new remote repository
git remote remove origin<br>
git remote add origin {repository url} | git remote set-url origin {repository url}<br>
git remote -v

# reset the local changes to match the remote
git reset --hard origin/main<br>
git push origin main

# use Git in VS Code (Without Terminal)
1. go to "Source Control" (Ctrl + Shift + G)<br>
2. click "Initialize Repository"<br>
3. click + (Stage All Changes)<br>
4. enter a commit message and click ✔️ Commit<br>
5. click ... (More Actions) → Push

# clone a GitHub Repository to VS Code
1. copy the repository URL from GitHub<br>
2. open VS Code Terminal (Ctrl + ~)<br>
3. run: git clone {repository url}<br>
4. open the cloned folder in VS Code: cd {your-repository}
