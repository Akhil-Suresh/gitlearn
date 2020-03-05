# Sync local to remote

Inorder to send local changes to remote

```sh
git push <server-alias> <branch name>
```

eg.

To push our local master branch to remote

```sh
git push origin master
```

Inorder to push the current branch and set the remote as upstream

```sh
git push --set-upstream origin master
```
or

```sh
git push -u origin master
```

Meaning remote branch gets tracked to local branch
so after running the last command from now on we can just do

```sh
git push
```

to send our changes to remote

