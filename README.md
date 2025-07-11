# Git SSH
1. `ls ~/.ssh`
2. `ssh-keygen -t rsa -C "your_email@example.com"`
3. `ssh-add ~/.ssh/id_rsa` 
4. `cat ~/.ssh/id_rsa.pub`

# Git management

## Three strategies
- merge
- rebase
- stash

## Task 1. start a new project
1. `git init`
2. `get branch --all`
3. Edit a file
4. `git add README.md`
5. `git commit -m "init project"`
6. Open git tab
7. Change default editor
  1. `git config --global core.editor "nvim"`

## Task 2. Create branch & Push to remote website
1. `git remote add origin YOUR_REMOTE_LINK_NAME`
2. `git branch -m main`
3. `git push -u origin main`

## Task 3. Create new branch to develop code 
1. Create new branch
  1. `git branch feature1`
  2. `git checkout feature1`
2. Quicker way:
  1. `git checkout -b 'feature1'`
3. Standard operation
  1. `git add`
  2. `git commit -m "edit message"`
4. `git checkout main`

