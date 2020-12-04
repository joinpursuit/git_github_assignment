# Git & GitHub Assignment

These assignments will help you get familiar with various workflows in git.

## Setting up

Step 0: Figure out what folder you will be doing these exercises in. If you don't know how to choose, create a folder in your `Home` directory called `sandbox`.

## Creating a git repo locally

`cd` into `sandbox` and create a folder in there called `git-practice-local`.

1. `cd` into the directory you will be working in. 
1. Initialize a git repository in the current directory using `git init`. This creates a hidden folder called `.git` which tells your computer that this directory is a git repository. 
1. Create a file called `README.md`.
1. Open the readme file with VSCode using `code .`
1. Write a haiku in the readme file. A haiku is a poem where the first line has 5 syllables, second has 7 syllables, and third has 5 syllables.
1. Add and commit the readme file.

You now have a git repo on your computer!

## Pushing a local repo to github

This assumes you did the previous steps already.

1. On `github`, create a new repository. Give it the name `git-practice-local`. **DO NOT CHECK ANY OF THE BOXES**
1. Make sure the **SSH** button at the top is clicked, not HTTPS.
1. Follow the second set of directions that say "...or push an existing repository from the command line". Run each of those commands in the terminal, in the directory that you created during the previous exercise.

You now have a local repo that is synced to github! You can push and pull without fear.

## Creating a repo on github first

1. On `github`, create a new repository. Give it the name `git-practice-remote`. **CHECK THE ADD A README FILE BOX**
1. `cd` to the sandbox directory
1. Clone the repo to your computer

You now have a repo that is synced to github!

Note the difference between this method and the one above is just about who creates the repository first. The end result is the same (though the contents of the files might be different, you can still push and pull).

## Forking & Pull Requests Solo Practice

These steps will walk you through forking and making pull requests. Practice this alone!

1. Fork this lesson by clicking the fork button on the top right of this page
1. Clone the **forked copy** to your computer
1. `cd` to the cloned directory
1. Create a new file called `haiku.txt`
1. `Add` and `commit` the empty text file
1. Write a haiku in the text file
1. `Add` and `commit` the changes
1. `Push` your changes up to your forked copy
1. On `github`, go to your forked copy and make a pull request.
1. In the title of your pull request, put your name 
1. In the description of your pull request, write a nice message to your instructors
1. Create the pull request
1. Pray that your pull request gets accepted by the maintainers of the project

## GitHub partner practice

In order to complete this part of the lab you will need to work with a partner. Only 2 people in a group!

Have one person be `Partner A` and another be `Partner B`.

1. **Partner A**: 
  * Create an empty `github` repository called `github-practice`. **Check the README box**.
  * Clone your newly created repository, giving you a local copy of the code on your machine.
  * Send Partner B the link to your repo on github

2. **Partner B**: 
  * Fork your partner's repository
  * Clone the forked copy to your computer.
  * Create a file called `haiku.txt`
  * Write a haiku inside the file
  * Add and commit the changes
  * Push the changes up to github
  * Create a pull request on your forked copy

3. **Partner A**: 
  * Accept the pull request 
  * Pull the latest changes down to your computer
  * Create another file called `haiku2.txt` and write a haiku inside it
  * Add and commit the changes
  * Push your code back up to github

4. **Partner B**: 
  * Add Partner A's repository _as a remote_ on your local machine. Use the clone (SSH) link, not the website address
  * Pull your partner's changes to your local machine (`git pull <remotename> <branchname>`)
  * Revert the last commit Partner A made, undoing their haiku
  * Add and commit your changes
  * Push your changes up to github
  * Make a pull request

5. **Partner A**: 
  * Accept the pull request
  * Pull the changes to your local machine. Both of you should now be looking at the same code.


