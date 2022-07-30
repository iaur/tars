# tars
A Power App based productivity tool

## To create a local copy (Coach)
1.  Create a folder and open cmd
2.  `$cd` in the directory
3.  Run `git clone https://github.com/rimgrs-ph/tars.git && cd tars` 
4.  Intialize directory `git init`
5.  Check branch you are in make sure you are in 'main' `git branch`
6.  Apply your changes to the local directory
7.  Check what change `git status`
8.  Add all changes `git add .`
9.  Commit `git commit -m "Your Message Here"`
10.  Push changes `git push`


## To create a new feature (Contributor)
1.  Create a folder and open cmd
2.  `$cd` in the directory
3.  Run `git clone https://github.com/rimgrs-ph/tars.git && cd tars` 
4.  Intialize directory `git init`
5.  Check branch you are in make sure you are in 'main' `git branch`
6.  Create a new branch `git branch branch-name`
7.  Change environment to the new branch `git checkout branch-name`
8.  Apply your changes to the local directory
9.  Check what change `git status`
10. Track all desired file changes `git add name.filetype`
11. Commit `git commit -m "Your Message Here"`
12. Push changes `git push --set-upstream origin branch-name`

## To create a bugfix branch (Contributor)
1.  Create a folder and open cmd
2.  `$cd` in the directory
3.  Run `git clone https://github.com/rimgrs-ph/tars.git && cd tars` 
4.  Intialize directory `git init`
5.  Fetch all the remote branches from the repository' `git fetch origin`
6.  See the branches available for checkout `git branch -a`
7.  Create a local branch and pull changes from the remote branch and check it out `git checkout -b bugfix-issues origin/bugfix-issues`
8.  Apply your changes to the local directory
9.  Check what change `git status`
10. Track all desired file changes `git add name.filetype`
11. Commit `git commit -m "Your Message Here"`
12. Push changes `git push`
