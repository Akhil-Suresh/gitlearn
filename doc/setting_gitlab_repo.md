# setting git in gitlab

Create an account in gitlab
Login to gitlab

Click on New Project
Name your git project and click create project

# Adding our project to gitlab

Inorder to add out project to gitlab we first need to set its remote.

```sh
git remote add origin git@gitlab.com:AkhilSuresh/git-learn.git
```

__origin__

Origin means url of the server we are pushing to . Its just an alias keyword for the server location. We can set it to any as we like.

meaning
```sh
git remote add githubaccount git@github.com:Akhil-Suresh/gitlearn.git
``` 