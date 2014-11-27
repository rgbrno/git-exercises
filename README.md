# Welcome to RailsGirls git exercises

This repository contains basic files for git exercises. You should create a fork under your github account and then start working on exercises below.

## Task #1 - setup your fork and clone it to your local machine

- [ ] create github account
- [ ] navigate to https://github.com/rgbrno/git-exercises
- [ ] click Fork button in right upper corner
- [ ] clone to your local machine by running `git clone git@github.com:<your nick>/git-exercises`

## Task #2 - update this readme

- [ ] edit README.md file in your local repository, mark all tasks from Task 1 and 2 as done by putting `x` in between `[ ]` like this `[x]`
- [ ] create a commit with this change
- [ ] push it to github so everyone can see the change, check the result on your github repository

hints:
* you have to add files to stage before you create a commit
* you can always see status by running `git status`
* `git add .` stages all your changes
* `git commit` opens your default editor so you can set commit message, after saving and quiting the editor, commit is created
* if this repository was created by cloning you can easily push the change back by `git push origin master`
## Task #3 - deleting junk and ignoring files

- [ ] you can see file with name junk in this repository, delete it
- [ ] create new file with name `.gitignore` that will contain just record - `password`
- [ ] create a file with name password, store some random text there
- [ ] create a new commit with all changes from above

hints:
* while deleting file will remove it from directory, it won't remove it from git repository, use `git rm` to do it
* .gitignore contains list of files to ignore in git, one record per one line
* if there's already a file under git control that you want to ignore you must delete it first in one commit and then ignore it in second, note that it will be still included in older commits

## Task #4 - travelling in time

- [ ] notice you can still see junk file in older commits (see github commits and their contents)
- [ ] see output of `git log`
- [ ] review difference between first and second commit in history

hints:
* every commit has unique identifier, use it as reference
* to display difference you can use `git diff <from reference>..<to reference>`


