# Data Analytics

Repository of the Data Analytics module at ZHAW.

> ℹ️ **NOTICE:** Please note that the weekly material will always be available shortly before the course starts.

## Folder Structure

Once the course is complete, the folder structure will look like this:

```
Data Analytics
├── .devcontainer
│   └── .devcontainer.json
├── Week_01
│   ├── ...
├── Week_02
│   ├── ...
├── Week_03
│   ├── ...
├── Week_04
│   ├── ...
├── Week_05
│   ├── ...
├── Week_06
│   ├── ...
├── Week_07
│   ├── ...
├── Week_08
│   ├── ...
├── Week_09
│   ├── ...
├── Week_10
│   ├── ...
├── Week_11
│   ├── ...
├── Week_12
│   ├── ...
├── Week_13
│   ├── ...
├── Week_14
│   ├── ...
├── .gitignore
├── README.md
└── requirements.txt
```

## Useful git commands 

Before running these commands, make sure you're in your working directory:

```bash
cd U:\Lektionen\DA_HS2023\data_analytics  # your working directory
```

### Clear git cache

```bash
git rm -r --cached .
git rm -r --cached ./foldername
git rm --cached <filename>
```

### Rebase

Rebase local changes on top of changes from the remote repository.

```bash
git config pull.rebase true  # run this once for working directory
git pull --tags origin main  # updates codebase
```

### Force Push and Pull to/from remote repository

```bash
git push --force
git pull --force
```

### Branching

```bash
git checkout -b week_01  # creates and changes to the new branch 'week_01'
git checkout main        # returns to main branch
```

Check out the Git Book on [Basic Branching and Merging](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
