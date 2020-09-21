## Repository
A repository in GIT contains all the files gathering all the versions of a given project.
To create a new repository the *git init* command is used to convert the current working directory to a git repository.

## Clone 
Clones a repository into a specified directory and will merge the current master branch with the one that is pulled. 
*git clone* repository name

## Fork
Forks are generally used to propose a change to be made to the project, it creates a copy of the main repository of a project to your working space. Then you make whatever desired changes then submit a pull request to the owner of the repository.

## Branch
Git branch allows you to create, delete, move, copy and do many more things to a given branch. A branch is simply a pointer to a set of commits, that can demarcate them to a given topic for example, a login functionality for a webpage.
*git branch* parameter nameOfBranch

## Commit
A commit takes the current state of the given contents, saves it locally in the working directory and can take a message to describe the changes.
*git commit* -m "Description of changes"

![Commit Diagram](https://media.geeksforgeeks.org/wp-content/uploads/20191122182103/staging_process.jpg)

## Merge
Takes changes from staged commits and merges them from one branch to another.
*git merge* otherRepo
This will take the updated commit from otherRepo and merge them onto the current branch you are on
![Merge Diagram](https://wac-cdn.atlassian.com/dam/jcr:83323200-3c57-4c29-9b7e-e67e98745427/Branch-1.png?cdnVersion=1251)

## Checkout
Checkout allows you to move between branches in a repository 
*git checkout* master
Switches to master branch
![Checkout Diagram](https://static.javatpoint.com/tutorial/git/images/git-checkout.png)

## Push
Updates a remote repository with commits from a local repository.
*git push* remoteRepo branch
This will push the current branch to the remote repository.

## Pull 
Used to retrieve and download content from a remote repository. It will first fetch all the content and then merge the remote content into the local repository.
*git pull* remoteBranch

## Remote Add / Remove / Show
Git show can show an object such as a tag, tree, or commit
*git show* object
Git adds changes that were made in the working area to the staging area
*git add*
Git remove removes files from the working branch
*git rm*

## Status
Git status allows you to see the state of the staged area and also the current working directory
*git status*

## Checkout
Checkout allows you to move between branches in a repository 
*git checkout* master
Switches to master branch

## Push
Updates a remote repository with commits from a local repository.
*git push* remoteRepo branch
This will push the current branch to the remote repository.

## Pull 
Used to retrieve and download content from a remote repository. It will first fetch all the content and then merge the remote content into the local repository.
*git pull* remoteBranch

## Remote Add / Remove / Show
Git show can show an object such as a tag, tree, or commit
*git show* object
Git adds changes that were made in the working area to the staging area
*git add*
Git remove removes files from the working branch
*git rm*

## Master Branch
The default branch in git, tends to be the main hub for the repository.


    
