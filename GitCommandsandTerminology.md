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

## Merge
Takes changes from staged commits and merges them from one branch to another.
*git merge* otherRepo
This will take the updated commit from otherRepo and merge them onto the current branch you are on
