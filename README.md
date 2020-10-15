# Git-Hub-Tutorial
Name:Matthew Adeyemi
Slack handle:@Marly

GIT AND GITHUB
- Git is a version control system used to track changes to code and for collaboration in projects. Version control can be done locally with git or remotely using an online version control system e.g github, bitbucket, etc

TERMINOLOGIES:
Commit: Is a type of save point in code which aid creation of multiple versions of project
Repository: A file in which you want to track file changes with git
Git setup: download  and install git bash for windows
Branch: Is a sort of an offshoot of your project which helps to safely implement new features without risking damage to existing code. N.B - By default the user is on the Master branch

COMMANDS:
git init: Initialize git in your project folder (telling git to track all folders and subfolders in this file path)
git add: Add files to the staging area(prepare them for commiting) can be used to add a single file(git add filename) or the entire folder(git add .)
git commmit -m message: Create a commit with -m to add a commit message for reference purposes
git push: Used to push the contents of a repository to an online repository:
git clone: Used to clone(copy) an online repository to your local computer

GIT FEATURES:
(It is assumed you have installed and opened git bash in your desired folder path): 

1 Create repository & adding a commit:
  git init
  git add . (add all files to the staging area)
  git commit -m message

2 push a repository to github
  repeat the steps above
  login to github/create account if you have none and create a new repository and select all options i.e private/public repository, set repo name, initialize readme file etc and create.
  open the repository & click clone or download and copy the repo path
  add the repo path to your local repository remote by using git add remote origin (git repo file path)
  push your local repo with the command git push origin master to push it to the master branch of your newly created git repo

3 clone repository
  repeat the steps in number 1 and copy the repo path you created
  in git bash type git clone file path


