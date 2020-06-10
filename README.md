# git_branches

- list branches: `git branch -a`
- create a new branch: `git branch <branch name>`
- create a new branch and switch to it: `git checkout -b <branch name>`
- push a branch to master: `git push origin <branch name>`
- delete a branch (never merged): `git branch -D <branch name>`
- delete a branch (already merged): `git branch -d <branch name>`
- merge a branch (must be in master): `git merge <branch name>`

## steps
 1. create a new branch
 2. pull from master
  - Start commiting to new branch
 3. push to master
 4. merge in master
