# Git vs Github

## Git
- A version control software meaning it tracks changes in source code over time.
- It is a distributed version control (DVCS) system meaning that every developer's working copy of the code is also a repository that can contain the full history of all changes.
- Main commands:
  1) pwd - Shows you where you are.
  2) ls - Shows you where you can go.
  3) ls -a - Shows you untracked files.
  4) cd <location> - Goes to <location>.
  5) mkdir <name> - Creates a directory.
  6) touch <name.filetype> - Creates a file.
  7) rm -rf - Removes a file.
  8) git init - Creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository.
  9) git status - Displays the state of the working directory and the staging area.
  10) git add <file> - Stage all changes in <file> for the next commit.
  11) git commit -m "comment" - A shortcut command that immediately creates a commit with a message.
  12) git push <remote> <branch> - Push the specified branch to <remote>, along with all of the necessary commits and internal objects. This creates a local branch in the destination repository.
## Github
- Github is a Git repository hosting service.
- It provides a web based graphical interface.
- Functions include:
  1) Forking - where one can copy a repository from one users account to another.
  2) Pull request where one can share the changes you've made to the original owner.
  3) Merge which incorporates the changes found in your repo to the original repo.

## What is .gitignore?
- Git sees every file in your working copy as one of three things:
  1) Tracked - a file which has been previously staged or committed.
  2) Untracked -  a file which has not been staged or committed.
  3) Ignored - a file that has been explicitly told to ignore.
- Ignored files are tracked in a special file named .gitignore that is checked in at the root of your repository.  
