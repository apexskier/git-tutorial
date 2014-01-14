# Outline

- Overview
 - What is git? Collaborative version control.
 - Why use git? Easier to try new things, easier to go back, less likely to lose work.
 - "Repository"

- Git setup
 - .gitconfig
 - GitHub
  - edu account
  - gui's
 - ssh keys
  - create
  - add to GitHub

- git init

- git status
 - tracked files
 - untracked files

- git diff
 - +/-

- git add
 - git rm

- git commit
 - commit message, name, email, default text editor
 - git commit -m
 - commit hash, branch, diffs

- git log
 - commit hash, author, date, message

- Branches
 - git branch
  - -va
 - much more you can do, switch between branches, move work between, test features

- Remotes
 - sync git repositories, regardless of location
 - Primary one for this presentation is GitHub

- git remote add <name> <source>
 - github
 - other servers
 - git remote -v

- git branch -va
 - can see remotes one added properly

- git push
 - git push -u <remote> <branch>, -u : upstream, sets main git pull/push
 - git push <remote> <branch>

- git pull
 - git pull <remote> <branch>

- git diff

- Workflow
 - especially when working collaboratively.
 - git pull, ...edit..., git add, git commit, git push, repeat

- Much more than this
 - git stash/pop
 - git checkout
 - patching
