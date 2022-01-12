# Assignment: Exploring Git
This assignment gives you a chance to explore basic use of Git and GitHub.

## Documents and Notes
* https://git-scm.com/
* https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class
* Git Hub Cheat Sheet https://training.github.com/downloads/github-git-cheat-sheet/
* Git Labt sheet https://about.gitlab.com/images/press/git-cheat-sheet.pdf

## Assignment 
* [lab-assignment-01](https://github.com/TELE36058-Software-Defined-Networks/lab-01-git-assignment/blob/main/lab-assignment-01.md)


## Reference
```
git clone REPO
```

Make a copy of a repository. A typical repository address is https://github.com/TELE36058-Software-Defined-Networks/lab-01-git-assignment.git

```
git add FILE
```

This can do one of two things. If FILE is not in the repository, it adds it to the repository. If FILE is already in the repository, it marks it as being part of the current set of files to be committed. (Often, you only want to commit only a subset of the files you've modified, so you use git add on each of those.)
```
git status
```
Get the status of your repository. What files have been modified? Which are staged for commit? Which are just new?
```
git commit
```
Commits all of the files you're added. Typically, pops up an editor. If vi pops up, use i to switch to insert mode, type the text for the commit, and then type the escape key to get out of insert mode. Then, type :wq to write the file and quit vi.
```
git commit -m "MESSAGE"
```
Commits the files you've added, using the given message. (A nice way to avoid the editor.)
```
git log | less
```
Shows a log of the changes that have been made. (less lets you page through those changes.)
```
git push
```
Send your commits to the primary repository.
```
git pull
```

Grab other people's commits from the primary repository.
