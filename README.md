# Step by Step setting up your project with git

## You can follow this guide to make a local repo of this guide by starting step one with this repo


This is going to run us through making a git repo, cloning the repo locally and  ultimately pushing your project to set yourself up for working in git.

1. make your git repo
2. open terminal and clone your repo (git clone <project-url>)
3. open your project in vscode (code <project-folder-path>) or 
`cd` into project folder and run `'code .'`
4. Open the terminal to branch your project and run command `git checkout -b new-branch-name`  
4. Inside `vsCode` make a change to a file.
5. Save your file.
6. Add the saved file to be prepped for commit `git add -A` will add all files changed
7. Now commit those staged files `git commit -m 'some--string-message-formed-in-the-imperative'`
8. Finally push those changes to github `git push origin new-branch-name`

