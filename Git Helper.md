<style>
r { color: Red }
o { color: Orange }
g { color: Green }
</style>


## Below is the template given by Github

### Push an existing repository from the command line

- git remote add origin https://github.com/ahamedshareef/desktop-tutorial.git
- git branch -M main
- git push -u origin main

### Create a new repository on the command line

- echo "# desktop-tutorial" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/ahamedshareef/desktop-tutorial.git
- git push -u origin main




|Name | State | Phone Number|
|---|---|---|
|Ahamed|Tamilnadu|9052222838|


# Git - Version Control


## 1.  Terms to know for beginners
- directory -> folder
- terminal Command line -> interface for text commands / CLI command line interface
- Know the workflow of git
- cd means change directory, code editor -> tools used to visualize and change your code
- Repository means -> where your project is placed or kept or group of projects is kept placeholder
- Git is a tool and GitHub is a website that can host your git repositories to showcase your work.

##  2. Basic Commands
-  git clone -> bring a repository that is hosted somewhere like Github into a local machine folder
-  git add -> tracking your changes and new files in Git.
-  git commit -> commit/save to Git.
-  git push -> from local push the changes / save the changes to remote repository/ Github
-  git pull -> Download the changes from remote to local
-  * repo -> repository
* `clone` -> bring a repo down from the internet (remote repository like Github) to your local machine
* `add` -> Track your files and changes with Git
* `commit` -> save your changes into Git
* `push` -> push your changes to your remote repo on Github (or another website)
* `pull` -> Pull changes down from the remote repo to your local machine

* `status` -> Check to see which files are being tracked or need to be committed
* `init` -> Use this command inside of your project to turn it into a Git repository and start using Git with that codebase


## Workaround for non-updating files and repositories
- git reset -hard
- git remote prune origin   -> deletes all the unreachable objects from the remote repository but it doesn't fetch them
- git gc --prune=now -> deletes all the files that are not reachable from the current branch

