# Git-Webinar
This repository will contain the instructions that are needed to complete the task for the git webinar held by CodeX on the 10th Of October 2020.

## Contents
* [Description of task](#desc)
* [How to make a pull request](#pull)

<a name='desc'>

## Description of Task
The basic motive of this task if to enable the participants to practice the commands learnt in the Webinar held.
Participants will have to make a branch and on that branch they will have to make a Pull Request that should contain a a code file (i.e. a file with the extension .c .py .html etc) and a basic Markdown file (a.k.a. README.md file).

The code file must have the following:-
  * Atleast 15 lines of code.

The Markdown file must have the following:-
  * An appropriate title.
  * Name of the the participant.
  
The task involves the following steps:-
  * Making a Branch in this [repository](https://github.com/CodeX-SFIT/Competitive-Programming-Pull-Request).
  * Making a folder in the directory relavent to your code file.
  * Making a Markdown file with the contents given above.
  * Commiting the changes.
  * Pushing the changes.
  * Making a pull request.

<a name="pull">

## How to make a pull request

### Here are the steps:-
   1. Fork the Repository
      
      You can fork a repository on GitHub by navigating with your browser to the GitHub URL of the open-source project you would like to contribute to.
      You can use the [our demo repo for practice](https://github.com/CodeX-SFIT/Competitive-Programming-Pull-Request)
      
      When you’re on the main page for the repository, you’ll see a **Fork** button on your upper right-hand side of the page, underneath your user icon:
      
      ![](https://github.com/CodeX-SFIT/Git-Webinar/blob/master/Images/fork.gif)
      
      Click on the fork button to start the forking process.
      
      Once the process is done, your browser will go to a screen similar to the repository image above, except that at the top you will see your username before the repository name, and in the URL it will also say your username before the repository name.
      This creates a copy of the repo under your GitHub account which includes all the code, branches, and commits from the original repo with the URL like: 
      ```https://github.com/your-username/Competitive-Programming-Pull-Request```
          
   2. Clone the Repository
      
      To make your own local copy of the repository you would like to contribute to, let’s first open up a terminal window.(*make sure you've already installed git*)
      We’ll use the ```git clone``` command along with the URL that points to your fork of the repository.
      
      ```$ git clone https://github.com/your-username/Competitive-Programming-Pull-Request.git```
   
   3. Make a new branch
      
      Once the repo is cloned, you'll nee to do the following steps:
         1. Create our new branch with the ```git branch``` command. Make sure you name it descriptively so that others working on the project understand what you are working on. ``` $ git branch new-branch```
         2. Now that our new branch is created, we can switch to make sure that we are working on that branch by using the ```git checkout``` command: ```$ git checkout new-branch```
         
      Alternatively, you can condense the above two commands, creating and switching to a new branch, with the following command and ```-b``` flag: ``` $ git checkout -b new-branch```
      
   4. Make Changes Locally
      
      Once you have modified an existing file or added a new file to the project, you can add it to your local repository, which we can do with the git add command. : ``` $ git add .```
      
      With our file staged, we’ll want to record the changes that we made to the repository with the ```git commit``` command.
      
      The commit message is an important aspect of your code contribution.If we have a very short message, we can record that with the -m flag and the message in quotes:```$ git commit -m "<Changes you've made>"```
      
   5. Push Changes
      
      At this point you can use the git push command to push the changes to the current branch of your forked repository: ``` $ git push --set-upstream origin new-branch```
      
   6. Sync Fork
     
      Next, we’ll specify a new remote upstream repository for us to sync with the fork. This will be the original repository that we forked from. We’ll do this with the ```git remote``` add command: ```$ git remote add upstream https://github.com/CodeX-SFIT/Competitive-Programming-Pull-Request```
      
   7. Create a Pull Request
   
       At this point, you are ready to make a pull request to the original repository.
       You should navigate to your forked repository, and press the “New pull request” button on your left-hand side of the page.
              
       ![](https://github.com/CodeX-SFIT/Git-Webinar/blob/master/Images/PRButton.png)
       
       ![](https://github.com/CodeX-SFIT/Git-Webinar/blob/master/Images/PullRequest.png)

   8. Conclusion
       
      At this point, you have successfully sent a pull request to an open-source software repository. Following this, you should make sure to update and rebase your code while you are waiting to have it reviewed. Project maintainers may ask for you to rework your code, so you should be prepared to do so.

      Contributing to open-source projects — and becoming an active open-source developer — can be a rewarding experience. Making regular contributions to software you frequently use allows you to make sure that that software is as valuable to other end users as it can be.
