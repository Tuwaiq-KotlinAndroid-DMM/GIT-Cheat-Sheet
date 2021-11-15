# GIT-Cheat-Sheet


### Team Leader
1. Create an empty GitHub repo
1. Locally, create an android project
1. `git init` 
1. Locally, `git remote add <git url>`. 
1. Confirm this with `git remote -v`
1. Create project file(s) and `git add -A` then `git commit -m '<relevant message>'`
1. git branch -M main
1. `git push origin main` push to repo main branch
1. `git checkout -b yourname-dev` to create dev branch and checkout to dev branch
1. Create a new file and `git add -A` then `git commit -m '<relevant message>'` 
1. `git push origin yourname-dev`
1. If you have a pull request pending, view the request and merge if and only if the code is perfect
1. Merge dev to main, when project is completed via pull request

<br>

### Teammates
1. Fork and clone team leader's repo i.e. `git clone <your forked git repo url>`. This will be your `origin`
3. run `git remote add upstream <team leader git url>`
2. run `git checkout -b yourname-dev` to create a dev branch
4. Create a new files (e.g.- `Any Activity`) and `git add -A` then `git commit -m '<relevant message>'` 
4. Run `git push origin yourname-dev`
5. Send a pull request to team leader
6. The team leader merges the code to dev.
7. Switch back to your dev branch.
8. Run `git pull upstream dev` to get current version from team leader locally. Your local dev branch should now be up to date with the upstream dev.
9. Continue working and sending pull requests to your team leader.
