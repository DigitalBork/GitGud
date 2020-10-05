This is just a quicky file for how to use git!

To clone a git repo into a folder on your machine for local development, just clone it.

git clone <repo>

Example:

git clone https://github.com/DigitalBork/GitGud.git

To branch out, we simply create a logicaly named branch

git branch <name>

Example:

git branch <staging>

Lets commit to an action. Git commits should have a simple but detailed comment! Nothing like "fixed bugs" as that does no one any good

git commit -m <commit>

Example:

git commit -m Finally posting my notes to GitHub.

Now lets swtich tracks and track a different branch! 

git checkout <branch>

Example:

git checkout staging

Lets not forget that we need to tell git to track files even when we make new branches (because you'd expect git to do that automatically but I'm not upset. Just dissapointed.)

git add <file> 

Example

git add *

For pull requests, AFAIK we accept them through the web interface? Feel free to submit a pull request with changes, suggestions, etc!

With <3, DigitalBork!
