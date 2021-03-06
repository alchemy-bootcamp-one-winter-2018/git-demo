# Git Demo

(:

##  Set up!
- `git init`
    - initialize a git repo in a folder
- `git remote add <name> <url>`
    - link my local repo to a remote repo on github

## Work
- `git status` 
    - see what's changed since I last commited
- `git add <filename>` or `git add .`
    - stage a change to add it to our timeline
- `git commit -m "what I changed or how it changed my app"`
    - commit staged changes to our timeline
- `git push origin master`
    - push any commits to github

## Branching
- `git branch`
    - list branches on local repo
- `git branch <name>`
    - creates a new branch
- `git checkout <name>
    - switches to specified branch
- `git checkout -b <name>`
    - create and switch to a new branch
    
## Deploy to GH-Pages
- `git checkout -b gh-pages`
    - gh-pages is the branch that will be published! so make sure it's what you want to publish
- in your browser visit: `<your-gh-username>.github.io/<repo-name>`
