# Repository

- A repository, or Git project, encompasses the entire collection of files and folders associated with a project, along with each file’s revision history. The file history appears as snapshots in time called commits, and the commits exist as a linked list relationship, and can be organized into multiple lines of development called branches. Because Git is a DVCS, repositories are self-contained units and anyone who owns a copy of the repository can access the entire codebase and its history. Using the command line or other ease-of-use interfaces, a git repository also allows for: interaction with the history, cloning, creating branches, committing, merging, comparing changes across versions of code, and more.*

# Checkout

- In Git terms, a "checkout" is the act of switching between different versions of a target entity. The git checkout command operates upon three distinct entities: files, commits, and branches. In addition to the definition of "checkout" the phrase "checking out" is commonly used to imply the act of executing the git checkout command.

# Commit:

![](https://user-images.githubusercontent.com/60896891/75190267-f0922880-571d-11ea-8edb-405d81305845.png)


- Commit is an individual change to a file (or set of files). It's like when you save a file, except with Git, every time you save it creates a unique ID that allows you to keep record of what changes were made when and by who.
- Commits usually contain a commit message which is a brief description of what changes were made.
- Commit set a message about the progressions you were finished. It saves all the changes made so that one can revert the code at any given time.


# Fork

- A fork is a copy of a repository that allows you to freely experiment with changes without affecting the original project.
- A forked repository differs from a clone in that a connection exists between your fork and the original repository itself.
- Your fork acts as a bridge between the original repository and your personal copy where you can contribute back to the original project using Pull Requests.
- Forking a project is as easy as clicking the Fork button in the header of a repository
- Once the process is complete, you'll be taken right to your the forked copy of the project so you can start collaborating!


# Clone
- When you create a new repository on GitHub, Clone exists as a remote location where your project is stored. You can clone your repository to create a local copy on your computer so that you can sync between both the local and remote locations of the project.
- Unlike forking, you won't be able to pull down changes from the original repository you cloned from
- If the project is owned by someone else you won't be able to contribute back to it unless you are specifically invited as a collaborator.
- Cloning is ideal for instances when you need a way to quickly get your own copy of a repository where you may not be contributing to the original project.
- To clone a repository, head over to the main page of a project and click the Clone or download button to get the the repository's HTTPS or SSH URL. Then, you can perform the clone using the `git clone` command in your command line interface of choice.


# Merge:
- Merging is Git's way of putting a forked history back together again.
- Git merge will combine multiple sequences of commits into one unified history. 
- Merge commits are unique against other commits in the fact that they have two parent commits.
- There are two main ways Git will merge: *Fast Forward and Three way*
- Git can automatically merge commits unless there are changes that conflict in both commit sequences.

# Push

-	The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch, but whereas fetching imports commits to local branches, pushing exports commits to remote branches.


# Branch:

- A branch is a unique set of code changes with a unique name.
- When you create a branch in your project, you're creating an environment where you can try out new ideas. Changes you make on a branch don't affect the`master` branch, so you're free to experiment and commit changes, safe in the knowledge that your branch won't be merged until it's ready to be reviewed by someone you're collaborating with.
- A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master . As you start making commits, you're given a master branch that points to the last commit you made. Every time you commit, the master branch pointer moves forward automatically.


# Pull
-	Pull Request is the way Github provides for author of the code to share his/her code with others, and to allow others to take a look at your code before you merge it to integration branch and leave comments. 

-	I assume you are using Github. Go to your Github repository and you will see tab called Pull Requests. 
 
-	Click on “New Pull Request” button.  
 






