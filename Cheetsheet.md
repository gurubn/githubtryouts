# Use Git bash to configure machine. Once you install Git , use will get it
git config --global user.name "gurubn"

git config --global user.email "******"

# To Edit or to see the git configuration
git config --global --edit

# Status of the repo
git status

# Track file git local
git add "file"'

# Track all files in the repo
git add .

# Commitssss
git commit "file"

git log

# Github connection
## Check ssh file present  in the system
$ ls -al ~/.ssh

# Generate SSH key
$ ssh-keygen -t rsa -b 4096 -C "bngurudatt@gmail.com"

# Git clone
* git clone "https or ssh"
* git add .
* git commit -m "comment"
* git push origin main

# Additional change added in github directly

# Git pull
git pull - It pulls and merges code if any changes

# Markdown syntax link
https://daringfireball.net/projects/markdown/syntax

# Git branches
* git branch [Branch name]
* git checkout [Branch name]
* git push -u [origin] [branch]

### Examples
git push -u origin add-more-instruns
git branch -r = show all branchs connected with repo