# GIT

 GIT PROJECT

Initializing a GIT Project

![](/img/01.init.png)

![](/img/02.commit.png)

![](/img/02-a.vi-msg.png)

![](/img/03.commit-msg.png)


Working with Branches

######   A git branch is used to creat different copy of a source code. In this new branch, one can proceed to make changes as suit, and this chnage is independent of the main copy. In practice, this is used to develop new feature on the application. As the initial code is untested it can not to be  added to the base code of the live application. Git branch is also useful for collaboration within remote environment , where developers can make diffrent branches while working on the same feature, and later converge all the branches to one branch.

Making the First Branch

![](/img/04.my-new-branch.png)

List your git Branches

![](/img/05.branch-list.png)

Change to an Old Branch

![](/img/06.switch-to-existing-branch.png)


Merge a Branch into Another Branch 

######  To merge two Branches A and B, and add the content of Branch B into A, we must first change into A and the git command  `git merge B` as shown below


![](/img/07.add-new-line.png)



![](/img/08.master-newbranch-merged.png)


Deleting A Git Branch

######  when a feature is added to an application, its often done in a feature branch. Usually this feature branch is deleted when the code must have been tested and merged into a staging or dev enviroment depending on the branch strateggy of the team. 






![](/img/09.delete-branch.png)



Collaborating and Remote Repositories

###### Github is a web-based platform where git repositories are hosted, by hosting our local repo on github it becomes avaialable to the public ( or shared privately)

Creating a Repository

###### Step 01 - click on the + sign at the top right corner of your github account , select new repository from the dropdown menu


![](/img/10.new-repo.png)

###### Step 02 - complete the form by adding a unique repo name and tick the box to add readme.md file . Step 3 - click the green `create your repository` button

![](/img/11.form.png)

Push Local Repo to Remote github Repo

###### Step 1  - generate SSH Key

![](/img/12.SSH-KEY.png)

###### Step 2 - Push the local repo to remote 


![](/img/13.push-to-remote.png)

##### Note you can also push from the terminal of your code editor by using typing the following commands, 1- `git status`, 2-`git add .` 3- ` git status` 4- `git commit -m "message"` 5- `git push`




Clone a Remote Repo

###### This is used for copying or downloading a remote link in github to a local machine where it can be worked on. NOTE - you can only clone into a folder with no git file.

![](/img/14.clone.png)

 


###### This is used for copying or downloading a remote link in github to a local machine where it can be worked on. NOTE - you can only clone into a folder with no git file.

![](/img/14.clone.png)

