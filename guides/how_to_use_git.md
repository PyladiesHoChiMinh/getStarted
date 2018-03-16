# Learn how to use `GIT`

### Overview

In this tutorial, you will learn step-by-step of how to use `git` as follows:

1. How to create an account for github
2. How to create a repo on github
3. How to clone a github repo
4. How to add a file and upload it to github
5. How to update new file from a master branch
6. How to create a new branch

Other important stuffs:

- What is github, anyway?
- What is a monorepo?
- Advantages of monolithic version control

#### What is github, anyway?

`Github` is a website allowing users to store their code as well as upload online. It is based on a concept of `git` which is a way to create, and manage different versions of source-code
 following a hirarchical structure.

 Technically, we call `git` as a distributed version control system with two main functions:
  - Tracking of how code is changed
  - Providing a method to allow developer manage different versions

![alt text](https://github.com/PyladiesHoChiMinh/getStarted/blob/master/images/Centralized-Version-Control-System-Workflow-What-Is-Git-Edureka.png)
#### What is a monorepo?

Monorepo is a "philoshophy" to manage code by one main branch a several other child branches.

Take an example, a main branch is called `master`. Following that, there are many child branches such as `branch_1`, `branch_2`. Whenever a child branch is updated, it will be needed to be updated by the main branch.

#### Why do we care about `github` and `monorepo`?

Imagine a team of three people Alice, Bob, and Chris. Each of you is given a task based on an `original master branch`.

Alice is working on her branch named `branch 1` and makes some modifications with two commits. Bob has five messy commits in two different child branches, say `branch 2a` and `branch 2b`. And Chris has only one, but it is updated fasten, say, `original new master branch`.

What should Alice and Bob do? When completing their work, should either of them merge their branch to `original new master branch`? The answer is NO. Indeed, `git` will prevent you from merging a child branch to master by informing a conflict and requiring you to resolve before taking any further action. In this case, either Alice or Bob origin branch is an old version of `master`.

For Alice, the simplest way is that she will have to create a new branch and move modifications to it.

For Bob, he needs to ascertain that all of his work in `branch 2a` and `branch 2b` should be merged into one branch, say, `branch 2`, then, follow what Alice's actions.

So, an idea here is that by using one master branch in one repository, any change will be updated. And if there is any issue related to branch, we can apply the same procedure to resolve all conflicts.


#### 1. How to create an account for github

Please go the website <https://github.com/> to register your account & fill in your name and email.

#### 2. How to create a repo on github

Please go to the following link <https://help.github.com/articles/create-a-repo/>

#### 3. How to clone a github repo

First method: Using Terminal/ Commander

`git clone HTTP_LINK_TO_REPO`

Second method: Using FTP

#### 4. How to add a file and upload it to github

Assume that this the first time you add a new file

`git add NAME_OF_A_FILE`

or to add all files at the same time

`git add .`

In case, you only need to add some modifications of file

`git add -p`

#### 5. How to update new file from a master branch

`git checkout master -- NAME_OF_A_FILE`

#### 6. How to create a new branch

`git checkout -b NAME_OF_A_NEW_BRANCH`

#### 6. How to get the latest update from `master`

`git checkout master` # Switch to `master branch`

`git pull --rebase`  # Get updates and keep current change.

### Read more

 - For more information of how `git` command works, please refer to [cheatsheet](http://files.zeroturnaround.com/pdf/zt_git_cheat_sheet.pdf )

#### Reference

 - [What is git?](https://www.edureka.co/blog/what-is-git/)
 - [Advantages of monolithic version control?](https://danluu.com/monorepo/)
 - [One vs. many — Why we moved from multiple git repos to a monorepo and how we set it up](https://hackernoon.com/one-vs-many-why-we-moved-from-multiple-git-repos-to-a-monorepo-and-how-we-set-it-up-f4abb0cfe469)
 - [Mono-repo or multi-repo? Why choose one, when you can have both?] (https://medium.com/@patrickleet/mono-repo-or-multi-repo-why-choose-one-when-you-can-have-both-e9c77bd0c668)
