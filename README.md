# Platform-Repo
A repository to act as a platform to house all SolarSpec repositories. Intended for ease of use

To view the status of all repositories:
```sh
git status
```
and to view the status of each repository:
```sh
git submodule foreach git status
```

Pull changes for every submodule:
```sh
git submodule foreach git pull origin main
```
or in case you have edited the files and need to stash changes:
```sh
git submodule foreach git pull --rebase --autostash origin branch_name
```
