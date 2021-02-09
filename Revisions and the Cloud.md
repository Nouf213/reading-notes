# Version control allows coders tl revisit various versions of a file by recording changes, it can also revert a file to its previous version.

By using **vcs** mistakes can be easily rectified.

## Git  has three versions:

* ***Local version control*** :  have been created many years ago by programmers it use one database on your hard disk to save changes.

* ***Centralised version control ***  : 
it allows programmers to have collaborations, it use single server to save your changes.

* ***distributed version control*** : it shows the main vulnerability of the cvs- the server as single point of failure if cvs goes down the collaborator cant work with each other,  to prevent this type of loss dvcs allows clients to creat mirrored repositories. 

**Git** is a :

* *Snapshots*: git is a dvcs that stores data in a file made of Snapshot it called commit.

* *Local operator*: this allows for process expedient  because a project's history resides on the local disk.

* *Tracking changes*: every single change applied to any file or directory is tracked by git.

* *Loss of data*: git minimise the possibility of a file damage such as accidentally lost data states committed, modified and staged.

## To get started with Git: 

* Install it with three ways:

   * Install as package. 
   * Install via another installer. 
   * Download and compile the source code.

## Setting up the Git repository: 

* Importing: import existing project or directory into Git
* Cloning: can also create a copy of an existing Git.

* Tracking and staging a new file:  git add file name ( to track single file)/ git add * ( to track all files in repository).

* Committing a file: git commit -m "the reason brief why" / git commit -a ( it is a snapshot of all modifications to tracked file in the working directory).

* Pushing changes: git push origin main ( push it to cloud)
Stashing changes ( git stash) is an option when you don't want to lose your changes but not ready to commit them git stash apply to retrieve hidden changes.
* Remote repositories: cloned repository the cloned repositories will automatically  give the name "origin" and the "main" is the name of your local branch.

Seeing your remotes through **Git remote** command it view the name of your remotes.