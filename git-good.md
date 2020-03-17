# Git Good

### What is Git?
- Git is a DVCS (distributed verison control system) made in 2005, that stores data in a file system made up of snapshots.

#### Git Terminology
- commit
	- a changed version of your project that is saved
- repository
	- a central location in which data is stored and managed
- tracked
	- files that are modified, unmodified, or staged. They were part of the most recent file snapshot
- untracked
	- files that were not in the last snapshot and do not currently reside in the staging area
	
#### Get Going With Git
Here's how you get started:

> Set up your user name and email address

```
git config --global user.name "[insert username"

git config --global user.email "[insert email address]"

```
> Clone your desired repository
```
git clone [repository URL]
```
> To determine the file states (which files are tracked abnd untracked
```
git status
```

