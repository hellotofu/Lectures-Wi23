## Version Control
---
- tracking changes (eg version history) is great to have 
> ## Version control 
>- version control enables many people to work on a single project 
>- each person edits their own copy of the files and chooses when to share those changes with the rest of the team
>- version control is a way to manage the evolution of a set of files (trackes the changes that have occured over time) 

> ## Repo 
>- Repository: the set of files 
>- home of different types of files 
>- most popular is git 
>- git is the version cntrl system (local) 
>- github is the hom where **git based projects** live on the _internet_ (remote) 

- you can clone remote repo to local repo 
  - first you $clone, $pull
  -  and then you can add your own stuff (add any files you want from your own repo) 
    - $add, $commit (note the change you made. give urself a message; make a record of things as you do them), and the $push (push changes to server; your changes from your local repo to a remote repo) 

- github is a remote host, the files are geographically distant from any files on your computer. 
- a github repo contains all the files and folders for your project 
- you can clone a github repo (remote) to your local repo (read: laptop) (?), you **clone** the repository (_look below_)

> ## Staging 
>- staging: you tell git which files you want to keep track of using **add** 
> **renditions used on the comand line**
> ![image](https://user-images.githubusercontent.com/82544669/213064165-8549b1bb-f361-49c3-a38e-988e8d71cc09.png)
>- kinda like asking git what to show you 

> ## Commit
>- making a "snapshot" of your files
>- when you make a commit to save your work, git creates a unique ID (SHA or hash) that allows you to keep record of the specific changes committed along with who made them and when 
>- commit tracks who, what, and when 
>- in version control systems, a commit is an operation which sends the **latest changes of the source code to the repository**, making these changes part of the head revision of the repository 
>- eg. git **comit** -m 'fix typos in car and prof' (just say what u did) 
>- push changes AFTER COMMIT TO THE REMOTE REPO 
>- each time you create a commit, git tracks the changes automatically 
>- you can return to the state of the repo at any commit. future commits dont disappear, they just arent visible when you **check out** an older commit

> ## Branch --? Merge
>- good way to experiment 
>- a way to create a brand new working directory, staging area, and project history 
>- branches allow you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repo 
>- always create a branch from an existing branch (usually, you made a new branch from the default branch of your repo) 
>- you could abandon a branch if you decide to not include the commits on the branch and push it to the main repo 
> ## Merge
>- Merge allows you to combine the commits from a branch back into the main 

> ## Fork 
>- after you fork a repo, you can tinker with it however (=
>- forks are best used when: the intent of the 'split' is to create a logically independent project (which may never reunite with its parent) 
>- _BRANCHES_ are best used when they are created as temporary places to work through a feature, with the intent to merge the branch with the origin 

> ## GUIs 
>- can give graph display of past development 
>- eg., github desktop, sourcetree, etc. 
>- GUIs can help when working with version control 

> ## Why version control with git and GitHub?
>- 1) collaboration (pull - change - push - woohoo) 
>- 2) returning to a safe state (sometimes when we have ideas, it'll give errors, this allows us to "undo")
>- 3) exposure for your work 
>- 4) tracking others' work 

> ## Pull Req
>- if you find a bug in someone's code, you can submit a pull request (PR)
>- the author then reviews your code/edits and decides whether or mot they want to merge your pull request 

> ## Word bank 
>- repo: set of files and folders for a project 
>- remote: where the repo lives (can this also be local?) 
>- clone: get the repo from the remote for the first time 
>- add: specify which files you want to stage/show (add to repo) 
>- commit: snapshot of your files at a point in time ("save button") 
>- pull: get new commits to the repo from the remote 
>- pull reqs (PR): allow you to make edits to others' repos 
>- issues allow you to make general suggestions to ur own or ppl's repos
>- commits: allow you to visit previous versions (bc each commit is assigned a unique hash) 
>- branches allow you to experiment (can be abandoned or merged) - good thing about open source software
>- can work on others' repos by forking their repo onto your github 
>- push: send your new commits to the remote 

> ## check status  
>- "git status" --> shows files in directory you havent added, changes you havent commited, etc. 
