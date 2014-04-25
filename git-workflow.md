# Basic Git/Github Workflow

## Assumptions

1. Starting from scratch; project is not created

## Steps

1. Create project directory on local machine
1. In terminal, navigate to newly created directory
1. Create a new git repo: `git init`
1. Add a *readme.md* file that states what the project is all about: `touch readme.md`
1. Add files to staging `git add .` (taking a snapshot)
1. Add files (snapshot) to local repo: `git commit -m "commit message"`
1. Go to [Github](http://www.github.com) and add a new repository
1. After you create repo, copy the "remote add" line, then paste back within your project directory in your terminal
1. Now push your local repo to Github: `git push origin master`