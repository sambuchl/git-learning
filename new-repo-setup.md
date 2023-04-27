# on Github, create a new repository WITHOUT a readme
# note the url, in format: https://github.com/repo-name/file-name.git

# on Mac, in Finder, option + click on directory name and Copy Path
# on Mac, in Terminal:
$ cd <paste path>
# initialize new git repository
$ git init

# create new branch main
$ git branch -m <new-branch-name>

# check status of files in repo
$ git status

# add files for tracking in the git repo
$ git add .

# commit files 
$ git commit "insert helpful message here describing commit>

# set the remote URL (where you will push the files
$ git remote add origin <REMOTE_URL_FROM_ABOVE>

# verify the new remote URL
$ git remote -v


# pushes changes from local repo to remove repo specified as the origin
$ git push -u origin main





# References
https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github
