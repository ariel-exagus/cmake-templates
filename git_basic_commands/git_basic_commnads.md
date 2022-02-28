# Guide of the Basic commands to use on Git

One of the first step to do is get an account in GitHub or BitBucket. You need to have a credentials to connect in remote way with the repositories.

## Initial configuration


## Daily commands

### 1- Git Init
This command allow to use git commands in your directory. This will create a `.git` directory

```
$ git init
```

### 2- Clone a repository
The first step to get a local copy of the repository is run a `clone` command. 

```
$ git clone [HTTPS_LINK_TO_PROJECT]
```

To clone the repository into a new branch.

```
$ git clone [HTTPS_LINK_TO_PROJECT] -b [new-branch-name]
```

### 3- git status
This command gives us all the necessary information about the current branch.

```
$ git status
```

With this command you can know if your local copy there are new files, deleted files or modified files.

### 4- git fetch
This command only fetches available updates in your branch.

```
$ git fecth
```

### 5- git pull
This command gets updates from remote repository. Is important that you make a pull before push your change on the remote repository, because in this way you don´t have conflicts with your changes.

```
$ git pull
```

### 6- git add
When you make a change in your file, you need to push this change into a stage status. You can do this with `add` command.

```
$ git add <path_file>
```

If you want to add all files, you have to run this command:

```
$ git add --all
```

