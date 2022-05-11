# Platform-Repo
A repository to act as a platform to house all SolarSpec repositories. Intended for ease of use for multiple repositories; an all at once up-to-date git pull command.

Use to view the status of all repositories:
*git status*
and to view the status of each repository:
*git submodule foreach git status*


Pull changes for every submodule:
*git submodule foreach git pull origin main*
or incase you have edited the files and need to stash changes:
*git submodule foreach git pull --rebase --autostash origin branch_name*
