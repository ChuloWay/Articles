# Introduction To GitHub


## Table Of Content

* Basic Introduction
* What Is GitHub?
* Why GitHub
* Git Vs GitHub
* Cloning In GitHub
* Pull Request
* Making A commit In GitHub
* GitHub Desktop Vs GitHub CLI

## Introduction

GitHub is a term that is frequently used in discussions about software development, in this article you will learn what it is and some of the basic functions it can accomplish.


## What is GitHub?

To fully comprehend GitHub, you should first understand what Git is.

<a href="https://git-scm.com/" target="">According to its official documentation,</a>
 Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
Therefore, GitHub is an online software development platform that makes use of Git, an open source version control technology used for project storage, tracking, and collaboration.


## Why GitHub?

Aside from being one of the biggest communities for programmers, using GitHub is cost-free if your project is publicly available and comes with a wiki and issue tracker that make it simple to provide more detailed documentation and obtain feedback on your work.

## Git Vs GitHub

Though the two complement each other, here are some differences to help you understand what they are.

 **Git**                              | **GitHub**                                         
:------------------------------------:|:--------------------------------------------------:
 Git was first released in 2005       | GitHub was released in 2008                        
 Git is maintained by Linux           | GitHub is maintained by Microsoft                  
 It is a local version control system | GitHub is a web-based hosting service        
 It is used in the Command Line       | GitHub has a graphical user interface              
 It is Completely Free                | GitHub has a free plan and it also has a paid plan 


## Cloning In GitHub

 ### What you need
* A GitHub user account
* GitBash, and
Git installed and configured on your computer, if you are having problem setting it up here is a <a href="https://www.simplilearn.com/tutorials/git-tutorial/git-installation-on-windows">Link</a> to an article to help you out.
* A Text-editor, for this article i will be making use of ```VScode``` 

Git clone is a Git command that creates a copy of an existing repository in a new folder. Each branch in the cloned repository has a remote-tracking branch created for it as youll. To obtain a development copy of an already-existing central repository, users most frequently use this command.


* you start by searching for a project repository that interests you and clicking on it to view its details. For instance, if you search for ```initial contributions```, clicking on it displays the picture below.

![Repo-Clone](photos/firstcontribution.png)

* Select the ```Code``` indicated green button on the right. Upon doing this, a drop-down menu with the choices``` HTTPS```, ```SSH```, and ```gitHub CLI``` will appear, as seen in the image below.

![Repo-Clone](photos/selectCode.png)

* For this Clone, you will choose the ```HTTPS``` option, which you switch to before selecting the copy icon.

![Repo-Clone](photos/httpsOption.png)

* Next you open your terminal, on your home screen you locate the search icon on the taskbar and type in ```gitBash```.

 * Once GitBash has been opened, you navigate to a folder on your local machine by using the ```cd``` command, on reaching your desired folder path, while connected to the internet, enter the Git clone command.

![Repo-Clone](photos/clone.png)

* Doing this successfully you have cloned the remote Repository to your local machine.

## Pull Request

A pull request, commonly shortened to PR, is an event that occurs in development project when a contributor is ready to add the changes he/she made to the main project repository.

How do you go about making a pull request?

* Create a local clone by forking the main repository. The contributor forks the main repository first, which they can clone onto their local system.

 ![Repo-Clone](photos/forkRepo.png)

 ![Repo-Clone](photos/CreateForkEdited.png)

 * If you go to your repository list you will see the forked repo amongst your repositories on GitHub

 ![Repo-Clone](photos/myRepo.png)

* Open your Terminal, Git Bash

* You then proceed to clone the remote repository to your local system, as shown prior to this section.

![Repo-Clone](photos/forkClone.png)

* To add a new branch to the repository, type the command line ```git checkout -b (name of the branch)```.

* Open your text editor VScode.

* Make the necessary local changes. you can then apply the necessary modifications to the code, whether you are working to fix a problem or add a new feature.

* To view the changes you have made, type ```git status``` in the command line.

* Then, enter ```git add .``` to include all the modifications you've made and tell Git that you want to incorporate them in the following commit.

![Repo-Clone](photos/gitBash.png)

* You should see a message summarizing the changes you made after typing ```git commit -m 'The Commit Message Of The Changes Made' ``` and pressing Enter.

* Finally, enter the command ```git push --set-upstream origin < branch name >.```

* You  will see a break down of files pushed and time spent and a message that your Git push was successful. Visit GitHub once more to view your pushed branch.


![Repo-Clone](photos/pushCode.png)

* Next You Go to your forked repository on GitHub and click on the right-hand side of the new branch to reveal a green button labeled "compare and pull request." Click that button to continue.

![Repo-Clone](photos/CandP.png)



* You can write a message explaining why you want to submit a pull request to the owner and possibly the modifications you made in the text box that is located below . Following that, select "create pull request." The maintainer will then assess the work done in the your forked repository and make any comments for some adjustments to be made or successfully Merge the Pull request.

![Repo-Clone](photos/makePr.png)


* You have successfully submitted a pull request; now you should wait for the repository maintainer to accept your request and publish the modification you made.


## What Is Git Commit And How Do you Make Use Of It?

The ```git commit``` command is used to save your changes to the local repository after making any necessary changes to the project you are working on.
Keep in mind that before using the ```git commit``` command, you should specifically tell Git which modifications you want to include. This implies that just because a file has been modified, it won't necessarily be added to the subsequent commit. Instead, you should indicate the required modifications for inclusion using the ```git add``` command.

You make use of ```git add <filename>``` to select the file to include, or ```git add . ``` to include all files in the folder., Then you commit using the Git command.

  ```git commit -m "commit message"``` the hyphen with m indicates that you want to add a message with the commit.

  ![Repo-Clone](photos/commitExample.png)


## GitHub Desktop Vs GitHub CLI
 **GitHub Desktop**                                                                       | **GitHub CLI**                                                                      
------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------
 It enables you to interact with GitHub using a GUI                                       | It is purely a command line tool                                                    
 It is simple to use                                                                      | It requires you knowing Git commands                                                
 It can't handle complex tasks\. The Help Manual advises to use command\-line Git instead | It gives access to every single Git command available and handles complex functions 


## Conclusion

Utilizing Git and GitHub for projects increases productivity and improves teamwork and as a beginner in software development it is essential to your career path. 
I sincerely hope that this article was useful in introducing you to Git and GitHub and explaining how they operate.



	


