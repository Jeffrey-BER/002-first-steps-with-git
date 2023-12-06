# How to use git in combination with GitHub and what basics have to be done

- This document discribes what to set up and what commands are needed

## Tipical Workflow

When starting a new repo / Project:

- creat a folder localy -> mkdir "folder-name"
- change directory in to that folder -> cd "folder-name"
- inizialize a new repo -> git init
- by default the main branch is called main
- to change the branch name -> git init -b "branch-name"

Adding something from a "changed", "created" or "deleted" to a stage

- adding a changed file "file-name.ending" to the index -> git add "file-name.ending"
- adds all changed files to the index / Stage -> git add \*
- adds all changed css files to the index -> git add \* .css

Commiting localy the stage

- Committing the stage -> git commit -m "massage what, why and where something was changed"

Note:
A massage should be left at any time!
if forgotten... a VI editor in the bash will be opened.
Leave the editor by tiping :q!

2BC
