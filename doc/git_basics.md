# Git learn

We are learning git here

## To initialize git repository

```sh
git init
```

## To check the status of current repository

```sh
git status
```

## Add user details to git

details about who is commitng the code.

```sh
git config user.name "Akhil"
git config user.email "akhilsuresh.work@gmail.com"
```

## To list out the configuration details

```sh
git config --list
```

## Basic git concept
There are two stages in adding a file in git

First stage is called *saving a snapshot*
Meanging telling the git we have some changes to add to git

It can be done by 
```sh
git add <file to commit>
```
eg:

```sh
git add README.md
```

Second stage is adding those changes to git

```sh
git commit -m "message to commit"
```

eg.

```sh
git commit -m "Initail commit"
```

## To list our commited changes

This command lists out all the details of the commit
```sh
git log
```

To list out commits message in singleline
```sh
git log --oneline
```


