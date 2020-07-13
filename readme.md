
# GIT Commands

## Clone repo in Local Machine

```cmd
~$ git clone repo_link
```

## Push a repo

```cmd
~$ git add .
~$ git commit -m "changes"
~$ git push origin master
```

## Pull a repo

```cmd
~$ git pull			//no need to address the repo link. As it already inside
```

## Create a new Branch

```cmd
~$ git branch NewBranch
```

## Switch over the NewBranch

```cmd
~$ git checkout NewBranch
```

## Make some changes in file on NewBranch then

```cmd
~$ git status
~$ git commit -am "adding something new"
~$ git log
```

## Push to repo on New Branch

```cmd
~$ git add .
~$ git commit -am "adding something new"
~$ push origin NewBranch
```

## delete branch locally

```cmd
~$ git branch -d localBranchName    //delete after merging

~$ git branch -D localBranchName    //delete without merging
```

# delete branch remotely

```cmd
~$ git push origin --delete remoteBranchName
```
