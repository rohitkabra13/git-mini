# Creating a Merge conflict

- Merge conflicts in git happen, when two branches were changed on the same line or in the same content of a file before a merge. If you just extend a file or append something, git usually just figures it out by itself.
- When git doesn’t know which version of a file to keep, it will insert some lines into the respective source code file and it will end up looking somewhat like this:

![](https://user-images.githubusercontent.com/60370214/75203065-298cc600-573b-11ea-93e3-78767411f7db.png)

# Resolving a merge conflict
 
- Usually there are only two scenarios when a merge conflict arises, you will either be putting changes from your branch into master, or you’ll be putting changes from master into your branch. The trick to avoiding merge conflicts is each time you have to put code from one branch into another, you just gotta figure out which of these two scenarios you are in.
## Merge my-branch onto master
- Say you are on master (and you’ve already run git pull), and you run…
                                                                                                                 (git merge my-branch)Git is putting the changes from your branch on top of master.
## Rebase master onto my-branch
- Say you are on my-branch, and you run…
                                                                            (git rebase master)
- Git is taking off the changes you made on my-branch, then it is putting the latest changes from master, and finally it puts your changes from my-branch back on top. It’s like the second frame of the sandwich-making GIF above, when the top slice of bread is removed. After that, the meat and cheese are added, and then the top slice is put back on top of the whole pile. That’s what git rebase does.
**The steps** - First, make sure to git pull the latest changes into master.
- Second, git rebase master into your branch. This will likely be the only time you get a conflict, and it should only be because someone else has changed the same code as you since the last time you rebased master, so it’s usually very easy to fix.
*Finally, whenever you want to merge your branch with master, make sure you do the first two steps right before, and then finally from master you can run git merge my-branch. Since your branch is totally up-to-date with master, Git will simply put your code on top of the master pile.*
