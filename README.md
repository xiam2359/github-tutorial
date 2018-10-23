# GitHub Tutorial

_by Xiaoqing(Mandy) Mei_

---
## Git vs. GitHub
#### Git is where you take a screen shot of yout work.
#### Github is where you: 
- a space where you can store your code 
- help track changes
- also provide option to collaborate on file
- requires git 


---
## Initial Setup
First, set up a github account.
1) got to https://github.com/ (you can click on this link)  
- To make a github account you need a email(if you don't have one you need to make one)
2) _Once you are on the site, you will first click **sign up**_
3) _Then create your username and password, type in you email address._
4) _After you fill them out, click **create an account**)_

---
## Repository Setup
First you have to have a repository that you've already created.
If you don't do the following to create a repository:
1. mkdir {name of your repository}

1. If you're at workspace, make sure you get into the repository before you set up
2. what you going to do is type `cd` [name of your repository]
3. 

---
## Workflow & Commands
Before you start do your workflow, you need t ounderstand what the codes below means  
- `git add .`-add file that are modified to the stage, not rename or deleted.  
- `git commit -m ""`-messages should be place inside of "", it is where you can take notes to tell yourself what have you change before you push it. Therefore, on github, the message will show to remind you whenever you are going back to work.  
- `git push`- send you saved command to github which is where you store your changes.
- `git status`- tells you whether your file is modified or not, and tells you what's going on generally. And when you did something wrong, it also tell you clues how to fix it.  
#### Now let's get on working!
After you've completed your repository setup, you will be able to work on your file.
1. Create a file
2. When you want to save your work that you've complete so far, you will first makesure you are `cd` into the repository where your file is on.
3. Then you type `git add .` to save your new changes.
4. Then you can type git commit -m "message" to remind yourself what have you add or change so far, so you can remember the next time you start working.
5. Last but not least, type `git push` to send the changes to github.
tips: use `git status` to check to make sure if you commit changes of the file or not. If it indicate the file name is color green , that means you've commit changes. There will also be messages aside to help you understand.



---
## Rolling Back Changes
#### Undo Edits
Before you undo any changes, you have to fork the 