# Git command cheatsheet

| Git command             | Git task                                         |
| ----------------------- | ------------------------------------------------ |
| git status              | List all files that have changed and their state |
| git add <filename>      | Add file to the stage                            |
| git commit -m "add foo" | Create a commit inluding all staged files        |
| git log --online        | Show the commit history                          |

## Using commits as backup

Restore to the last committed state

> git restore

Restore individual files:

> git restore <filename>

## Connect to remote repository

> git remote add origin git@github.com:GitHubUsername/repository-name.git  
> git branch -M main  
> git push -u origin main

## Cloning existing repository

> git clone <url>

## Synching local repo with remote repo

> git push  
> git pull
