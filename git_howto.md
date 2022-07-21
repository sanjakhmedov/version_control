# How to work with git

![Orange](orange.png)

### Here you can read the [Git documentation.](https://git-scm.com/doc)
---

## Setting up:

## Adding files and commiting:

## Branches:

## Remote repositories:

To work with remote **Repositories** there are number of platforms, one of the most popular one is GitHub. Git and GitHub are completely different instruments. On GitHub we can keep our repositories to work with a team. And Each team member can see the progress and commits that were made by their teammates. To creat a remote repository first we need to get authorized on GitHub and create a repository on it and copy the link to newly created repository. Then we do following actions: 

```sh
git remote add origin repo_link
git branch -M main
git puch -u origin main
```
Now we linked our local and remote repositories.
We can now push our changes that we made locally to remote repository on GitHub:

```sh
git push
```

Or, if we missed chenges that our teammates made, we can pull the most actual code by this command:

```sh
git pull
```

One more useful command is:

```sh
git clone repo_link
```

It clones a remote repository to our computer.

Added a new line to make a pull request.

---