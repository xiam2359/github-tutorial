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
4) _After you fill them out, click **create an account**_

#### Then create SSH key between github and c9
1) First click on the profile icon on the top right corner
2) Then click setting
3) Under personal seetings, click on SSH-GPG
4) Type "Cloud9" in the title.  
##### After that, you open your cloud9 tab.
5) On the top right corner of the tab, you see the gear icon, so click on it. 
6) Under account, you are going to find "SSH Keys" and click on it.
7) Copy and paste your second SSH keys into github
#### And you're done!
---
## Repository Setup
To make a repository, you have to start from your worksapce. Therefore, make sure you're `username:~/workspace`.  
1) type `mkdir "name of your repository"` 
2) After you created your repository, make sure you always `cd` into your repository if you're going to work on it.  
3) Type `git init` to initialize it.
4) Now you can type `touch README.md` to create a file, README.md is the file you created.
      - Now you can type anything or any of your work here.  
5) So to save your work, you are going to first type `git add .` , then `git commit -m "you message"` to mark down notes to remind your self what you have done the next time you come back to work on it.  
##### Next you switch your tab to github
6) Find the plus sign (+) at the top-right corner and click on it.
      - click new repository
7) name your repository the same one sa the one you name on Cloud9
8) After that, just click create repository.
9) Then make sure you are on the SSH mode instead of HTTPS  
        - You will then copy and paste each command under "...or push and existing repository from the command line" one by one.

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