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

# Commit
git commit "file"

git log

# Github connection
## Check ssh file present  in the system
$ ls -al ~/.ssh

# Generate SSH key
$ ssh-keygen -t rsa -b 4096 -C "bngurudatt@gmail.com"

# Git clone
git clone "https or ssh"