# Git & GitHub Assignment

This lab is divided into 2 parts, the first part focuses on Git and the second is real life example using GitHub. 

## Practice git branching

Go to [Learn Git Branching](https://learngitbranching.js.org/) and read the introduction.

Solve the exercices following the below order:

- Main > Introduction Sequence:
  - 1: Introduction to Git commits
  - 2: Branching in Git
  - 3: Merging in Git

- Remote > Push & Pull -- Git Remotes!
  - 1: Clone Intro
  - 2: Remote branches
  - 3: Git Fetchin'
  - 4: Git Pullin'
  - 5: Faking Teamwork
  - 6: Git Pushin'
  - 7: Diverged History

## GitHub practicce

In order to complete this part of the lab you will need to work with a partner.

1. *Partner A*: Create an empty [GitHub](https://help.github.com/en/articles/creating-a-new-repository) repository `gitHub-practice`.

2. *Partner A*: Clone your repository, giving you a local copy of the code on your machine.

3. *Partner B*: [Fork](https://help.github.com/en/articles/fork-a-repo) your partner's repository and you should fork.

4. *Partner A*: Add your partner's GitHub fork as "remote". You can name the remote whatever you want (except `origin` which would already be taken by your own GitHub repo).

---

To check everything is properly set-up, type `git remote -v`,you should have two 'remotes':
- `origin` pointing to your repository
- `theRemoteBranch` pointing to your partner's repository

---

5. *Partner A*: Make a new directory `Practice` and create a file `index.js` and write "GitHub keeps meticulous track of all the changes made to a project".

6. *Partner A*: Push your changes to the remote repository.

7. *Partner B*: Pull your partner's changes to your local machine.

8. *Partner B*: Go to the index file and add the following sentence: "In order to do so, you save these changes by commiting them. In order to commit them, you have to first tell Git to stage them."

9. *Partner A*: Pull your partner's changes to your local machine.

10. *Partner A && Partner B*: Both of you create their own branch. Add a new folder with a file. Add, commit and push your work to the remote repository.

11. *Partner A && Partner B*: Pull the changes to your local machine. Each of you should have access to your partner's new folder and file.

Branch naming conventions:
- Choose short and descriptive names
- Use lowercase in branch names
- Use hyphens to separate words

## Bonus

Go back to [Learn Git Branching](https://learngitbranching.js.org/) and work the other exercices.