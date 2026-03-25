# GitHub Tutorial

### 1. Basic Terminal Commands.
  - ```pwd``` (means: print working directory) - Checking current dirrectory
  - ```ls``` (means: list) - Checking folders & files in current dirrectory
  - ```cd foldername``` (means: change directory) - Go to folder (in example foldername is name of folder)
  - ```mkdir foldername``` (means: make directory) - Create a new folder in current dirrectory (in example foldername is name of folder)
  - ```touch filename.txt``` - Create a new file with any file format in current dirrectory (in example filename.txt is name of file)
  - ```rm filename.txt``` (means: remove) - Delete a file in current dirrectory (in example filename.txt is name of file)
    - ```rm -r foldername``` - Delete a folder (WITH ALL FILES INSIDE!) in current dirrectory (in example foldername is name of folder)
  - ```anycommand --help``` - Check documentation of this command

### 2. Creating and Setup New Repository.<br/>
1. GitHub.<br/>
1.1. Go to GitHub and create New Repository.<br/>
2. Visual Studio Code.<br/>
2.1. Open Git Bash Terminal and use this commands (After creating a new repo in GitHub you can copy this commands and paste in VSC Terminal)
  - ```git init``` - Creating a new Git Repository in your current folder
  - ```git remote add origin https://github.com/yourprofilename/yourreponame.git``` - Connecting your local Git Repository (Repo on your PC) to a remote repository (Repo on GitHub)  
  - ```git branch -M main``` - rename your current branch to main

### 3. Work with files.<br/>
1. Sent/Update files from PC to GitHub.
  - ```git add filename.txt``` - stage changes — meaning you tell Git which files you want to include in the next commit (in example filename.txt is name of file)
  - ```git commit -m "message"``` - save (commit) your staged changes with a short description
  - ```git push -u origin main``` - upload your commits to a remote repository (GitHub)
2. Sent/Update files from GitHub to PC.
  - ```git pull``` - download and update your local repository with changes from the remote repository (GitHub).
