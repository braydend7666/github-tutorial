# My GitHub Tutorial! 

_by Brayden DAngelo_

---
## What is Git? How does Git differ from Github?

I see you are going to start using Git and Github! I mean why else you you be here? Before starting Git/Github you probaly should know what it is used for, and why we use it. In addition it would be wise to know the differece betwwen Git and Github. Let's start with Git! Git is a version control system, primarlily used to track and change files faster then clicking and dragging. Git is used to organize files and is a very usefull tool for programers and people alike. Github is a host for software developers to share and collaberate on version control software aka Git. Github is usefull because you are able to veiw, copy and change code to help others or yourself. 



---
## Initial Setup
Now that you know what Git and Github are you will have to set up your ide (Integrated development environment). What the heck is an Integrated development environment you might be asking! It is a platform that software devoplers can code on. But before you start, you need to make a GitHub account. So log onto https://github.com/ and sign up. Once logged in go to this link (https://github.com/hstatsep/ide50/blob/master/README.md) and follow the directions.

---
## Setting up a repository 
Now that you are all set up and ready to start learning git you need to make a repository.In your IDE type ```mkdir repo-name``` , You can change the repo name but make sure it is all lowercase and instead of spaces use ```-```   .On https://github.com/ click the + button on the top right. Then press the first option. Enter a name that you put in your IDE and a description if you want to. Don't click the add README.md box for now. Then click the green button. Copy and paste the second box into your command line. It should look like this... 

```
git remote add origin git@github.com:your-name/repo-name.git
git push -u origin master
```
---
## Workflow & Commands
The basic workflow of git is add commit push! Add commit push! Again and again! Right now this sounds like gibberish! But I will explain. Think of a photographer taking a picture. ```git add``` The photographer puts a person in the camera's field of view. You add a change to the staging area. ```git commit``` the picture is taken and saved. Whatever was in the staging area is saved and taken off the staging area. ```git push``` The photographer sends the picture away. What was commited is sent to github. 


Here are some commands you will need to know:
* ```mkdir``` - makes a directory  
* ```rmdir``` - removes a directory   
* ```mv file-name.txt repo-name``` - moves a file          
* ```touch file.txt``` - makes a file       
* ```c9 file.txt``` - opens a file      

---
## Rolling Back Changes
We all are human, so we make mistakes. Somtimes we want to go back to a previous commit. This is where Git really shines, as I said earlier, Git is a version control system. This means you can undo changes when you want by using a simple command. ```git revert HEAD```. This will undo your latest commit! So if you have a change of heart you can undo what you did! But what if you want to redo a past commit after you commited more? First use ```git log``` and copy the very long code ex.  ```7310b6c60411e2c41c9cc41659bdf62f73d861ab```. Then put in the command line ```git revert 7310b6c60411e2c41c9cc41659bdf62f73d861ab```. 
