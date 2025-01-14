# Github

# what is git

Version controls help you to manage and track code changes overtime
Distributed means that every developer have a copy of that codebase
Distributed Version control system or VCS and it helps developers track changes in their code base also allows them to collaboraten with others and manage multiple versions of the project

GIt is Decentralized, which means you don't need a central server. Instead every developer has a full copy of the repo on their machine

<!-- Tracking files & making commits -->

```sh
git init

git add .

git status

git log

git checkout <number>

git checkout <name>

# switch from master to main
git branch -M main
```

<!-- HEAD -->

git heads is used to point to the current file

<!-- Branches -->

```sh
git branch <branchname>  # for creating a new branch

git checkout -b <branchname> # for creating a new branch and checkout to that branch

git branch new-branch source-branch # for creating a branch in the source branch
```
