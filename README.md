# DISCLAIMER

This is a quick little dive into Git. Git has many more features than I know about myself and more than anyone could ever hope to master overnight. It will take weeks, if not months to master Git.

## Cloning a repo to your current directory

>git clone <repo>

Example:

>git clone https://github.com/DigitalBork/GitGud.git

## Creating a new branch in your current rebo

To branch out, we simply create a logically named branch

>git branch <name>

Example:

>git branch <staging>

# Commiting changes to your repo

Lets commit to an action. Git commits should have a simple but detailed comment! Nothing like "fixed bugs" as that does no one any good

>git commit -m <commit>

Example:

>git commit -m Finally posting my notes to GitHub.

Now lets switch tracks and track a different branch!

>git checkout <branch>

Example:

>git checkout staging

# Telling Git to track more files on your repo

Lets not forget that we need to tell git to track files even when we make new branches (because you'd expect git to do that automatically but I'm not upset. Just dissapointed.)

>git add <file>

Example

>git add README.md


# An example Git workflow

>git clone https://github.com/DigitalBork/GitGud.

*edit / create files*

>git add * or git commit -a
>git commit -m "Added example workflow with git!"
>git push

# How to delete a branch

>git branch -d <branch name>

Example:

>git branch -d testing

# How to add a remote repo

>git remote add <git remote>

Example:

>git remote add https://github.com/DigitalBork/GitGud

**For pull requests, AFAIK we accept them through the web interface? Feel free to submit a pull request with changes, suggestions, etc! I work mostly from the terminal / Atom / the web interface**

# Useful links

### The GitHub Markdown Cheat Sheet
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

With <3, DigitalBork!
