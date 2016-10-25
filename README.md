# GitHub Tutorial
Today we will all be learning how to use `GitHub`. It is a service web-site that you can use to research any information that can provide you with any assistance. This website is also about creating your own repositories for people to view. Not only will you be learning `GitHub` today, but you will also be able to learn `Git` and how it works.

by [RalphA6189@hstat.org](RalphA6189@hstat.org)

---
## Git vs. GitHub
`Git` and `GitHub` are one of the many things you will have to learn in case  anybody ever asked you what is the difference between `Git` and `GitHub`.
* `Git` 
  * `Git` does not require `Github`
  * When you edit the files it saves along the way 
  * Add files, commit them

* `GitHub`
  * `Github` stores code in the cloud 
  * Requires `Git`
  * Visually see what you change
  * Easily collaborate files 

These are one of the many things you will have to learn about `Git` and `Github`.

---
## Initial Setup

* GitHub setup account steps

  * you will need a `GitHub` account which you can recive on the website.
[GitHub.com](https://github.com/)
  * Go to sign up 
  * Follow the instructions of what it says to create your account
  * Lastly you made your own account and welcome to `GitHub`

SSH in `Github` is used when it comes to making a repo on cloud9 you want to make sure you always click on SSH when creating a repo. GitHub will ask you that. Then you will be asked to copy and paste certain things to your cloud9 code to make sure `GitHub` is connected to your cloud9 repo.

---
## **Repository Setup**
To make a Repository you need to do this list of steps.  

1. Sign in to your c9.io account if u don't have one here is a link to get started and click "sign up". Follow the instructions once you get in. [cloud9](https://c9.io/)   

2. Create a work space in the account to get started.

3. To make a repo (Repository) you neeed to go to "window" and click "New terminal".

4. You should see `workspace`in the terminal stay on that workspace for now. Then as you are in that terminal type `mkdir` and then a title name you want to create.

5. Next you want to click `cd` and the title name of your file and it will take you to that file.

6. You then want to type `git init` and it will turn your file into a repo. You should be able to notice it should say `(Master)` you will then know it willl work.

7. Once you have done all of this you next want add any information to that file. Type `touch` and a title name for that by doing this you will create a folder in that file.

8. Open that folder in your file, clicking on it would be to easy so to open it type `c9` and your title of the one you made with `touch`. It will then take you to that folder.

9. Make sure to save your work.

10. Then type your information on that folder. Once you do that whenever you are done type in your terminal `git add .` this will let you add a change to your folder.

11. Type on that folder `git commit -m` and then a message to the computer of what you made, it can be short and simple for it to understand.

12. It will save your changes you have made in that folder.


---
## Workflow & Commands
There some things you will have to understand in order to use `GitHub` really well when making your repo on cloud9. There are some commands you will have to understand and learn that way you can always get the job done faster.

Here are some commands to begin with

First there is `git status` it let's you check to see if any changes you made are in order.
Then there is `git add` this let's you make any changes you can make to the current repo you are in.  
NOTE: You have to `cd` into that repo first to make that change it will not work if you do it in `workspace`.  
`git commit -m` will have you to create a message to the computer letting it know of what kind of changs you make to the repo.  
NOTE: You will have to be specific on what you did to the changes so the computer can understand what happened. For examble: `git commit -m ` and then your message. This will let the computer know of what change you made.  
Lastly `git push` can put all of the changes you made on your repo to `github`then you can see what changes were made.

---
## Collaboration
There may be some times where you might work with others on a big project on `GitHub` so do things like this on `github` you will need to learn how to **fork** and `clone`. When **forking** you are making changes to the repo on your cloud9 account to make the repo better together with the owner.

How to **Fork**
 
 * In your account you look at your profile pick and right beside it you should see fork on there click on it.
 * After you did that click on "clone or download".
 * Click on the little clipboard.
 * Then go to your c9.io (cloud9) account and into your workspace.
 * In workspace open your terminal (look in repo setup to find out how).
 * Then type `git clone` and paste the URL you copied. 
 * By doing that you have cloned that work to cloud9.
 * Then you must save adn do these things `git add` , `git commit -m` , and `git push` don't forget your message.
 * Then submit a pull request on your `Github` account. 
 * Create a pull request on your account make sure its on "Branch: Master" that way you can submit your changes to the owner of that repo. So then the owner will decide if they like.
 One tip `git pull` is a command where you are pulling the changes someone has made to the repo.