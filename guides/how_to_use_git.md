### Overview

In this tutorial, you will learn step-by-step of how to use git as follow:

- How to create an account for github
- How to create a repo on github
- How to clone a github repo
- How to add a file and upload it to github
- How to update new file from a master branch
- How to create a new branch

Other important stuff:

- What is github, anyway?
- What is a monorepo?

### What is github, anyway?

`Github` is a website allowing users to save their code as well as publish on internet.
 It is based on a concept of `git` which is a way to create, and manage different versions of code
 following a tree structure.


### What is a monorepo?

Monorepo is a "philoshophy" to manage code by one main branch a several other child branches. Take an example,
a main branch is called "master". Following that, there are many child branches such as `branch_1`, `branch_2`.
Whenever a child branch is updated, it will be needed to be updated by the main branch.

### How to create an account for github

Please go the website to register your account.

Fill in your name and email

### How to create a repo on github

### How to clone a github repo

First method: Using Terminal/ Commander

`git clone HTTP_LINK_TO_REPO`

Second method: Using FTP

### How to add a file and upload it to github

Assume that this the first time you add a new file

`git add NAME_OF_A_FILE`

or to add all files at the same time

`git add .`

In case, you only need to add some modifications of file

`git add -p`

### How to update new file from a master branch

`git checkout master -- NAME_OF_A_FILE`

### How to create a new branch

`git checkout -b NAME_OF_A_NEW_BRANCH`

### Read more
https://help.github.com/articles/create-a-repo/
