# Git & GitHub Assignment

This lab is divided into 2 parts, the first part focuses on Git and the second is a practice exercise using GitHub and a partner. 

## Practice Git branching

Go to [Learn Git Branching](https://learngitbranching.js.org/) and read the introduction.

Solve the exercises in the following order. If you get stuck on any level, you can type `reset` to start over.

- Remote Tab > Push & Pull -- Git Remotes!
  - 1: Clone Intro
  - 2: Remote branches
  - 3: Git Fetchin'
  - 4: Git Pullin'
  - 5: Faking Teamwork
  - 6: Git Pushin'

## GitHub practice

In order to complete this part of the lab you will need to work with a partner. Only 2 people in a group!

Have one person be `Partner A` and another be `Partner B`.

1. **Partner A**: 
  * Create an empty [GitHub](https://help.github.com/en/articles/creating-a-new-repository) repository called `github-practice`. **Check the README box**.

2. **Partner A**: 
  * Clone your newly created repository, giving you a local copy of the code on your machine.

3. **Partner B**: 
  * [Fork](https://help.github.com/en/articles/fork-a-repo) your partner's repository
  * Then clone it.

4. **Partner A**: 
  * Add your partner's GitHub fork as a remote repo. You should name it **Partner B's first name**. 
  * To check everything is properly set-up, type `git remote -v`, you should have two remotes (though it might show as four):
    - `origin` pointing to your repository
    - `partnerB'sFirstName` pointing to your partner's repository

5. **Partner B**:
  * Add Partner A as a collaborator on your fork. This is done on github.

5. **Partner A**: 
  * Make a new directory `practice` and create a file `index.js` inside of it.
  * Open the file and write "GitHub keeps meticulous track of all the changes made to a project".

6. **Partner A**: 
 * Push your changes to the **remote** repository, not origin

7. **Partner B**: 
  * Pull your partner's changes to your local machine.

8. **Partner B**: 
  * Go to the index file and add the following sentence: "In order to do so, you save these changes by commiting them. In order to commit them, you have to first tell Git to stage them."
  * Commit and push the changes 

9. **Partner A**: 
  * Pull your partner's changes to your local machine.

10. **Partner B**: 
  * Add a new folder called `haiku` with a file `haiku.txt`. 
  * Write a [haiku](https://en.wikipedia.org/wiki/Haiku) in the file, about any topic you like.
  * Add, commit and push your changes to the your repository.

11. **Partner B**: 
  * Make a pull request!

12. **Partner A**: 
  * Merge Partner B's pull request.
  * Pull down the changes to your machine.

13. **Partner A**: 
  * Do a `git revert` reversing **Partner B's** last commit
  * Push your commit to the remote (not origin) repo

14. **Partner B**: 
  * Pull the changes to your local machine. Both of you should now be looking at the same code.

