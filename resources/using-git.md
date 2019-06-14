# Using Git

## Getting started

0. Install _**git**_ on your computer, and get familiar with working on the _**terminal**_

1. You need to "clone" the repository from Github to your computer

    - In the terminal go to a directory on your computer where you would like the '_experiential_learning_club_' folder to be.
    - Then in the command line type & run the command:
    > git clone https://github.com/kish10/experiential_learning_club.git

2. Checkout the branch for your project
    
    > git checkout projects/project-name

    For example
    > git checkout projects/fashion-trends

## Adding files to the repository

Make sure you are in the **correct git branch.** Edit and files to the repository on your computer only when you are sure of being in the correct branch.

There are 3 steps in git you'll need to go through:  
    - **Add** files so git can track them,   
    - **commit** changes into git so git can fix the current state of the branch/repository as a point of reference,  
    - **pull/push** the changes into the main repository on Github.

0. Make sure you are in the correct git branch.    
  
    Add or edit files that are inside the repository on your computer.  
(what are the naming convetions for the files ?)

1. **Add** files to be tracked. On the terminal: 
    - go inside the repository directory
    - to see the untracked changes run the command
    > git status
    - to track specific files run the command
    > git add FILENAME
    - to track all changes run
    > git add .

2. **Commit** the changes into git:
    - run the command 
    > git commit -m 'Commit message.'
    
        (what is a good commit message ?)

3. **pull/push** into the main repository:  
    - To make sure that the branch/repository on your computer is the most upto date repository run the command:
    > git pull
    - To push your changes into the computer run the command
    > git push


## References
BetterExplained.com  
[A Visual Guide to Version Control](https://betterexplained.com/articles/a-visual-guide-to-version-control/)  
- Good in depth getting started/reference

Git Documentation  
[Git Branches in Nutshell](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)  
- Visually goes through git concepts & explains the commands.

Roger Dudler  
[git - the simple guide](https://rogerdudler.github.io/git-guide/)  
- "Visual" git reference.