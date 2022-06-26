# Git flow: Manchester Codes Jan 22 Cohort
Repo for demonstrating git workflow

## Workflow
![workflow diagram](./github-workflow.png)

## Exercise

### 1. Clone repo to your machine
Everybody clone down the repo to their local machines. Some students to create local branches and create a `.txt` file with a list of authors / bands / games / pokemon / whatever you want. Name it after your chosen subject and enter a few items (remaining students to make a note of their own short lists in the meantime).
Some useful commands:
```
git status
```
```
git checkout -b <your-branch-name>
```
```
git switch
```

### 2. Commit and push the changes to the repo
Some useful commands:
```
git status
```
```
git add -p
```
```
git log --oneline
```
```
git branch
```
```
git remote -vv
```
```
git diff
```

You should see your branch appearing in the repo in the browser

### 3. Open a pull request to the `main` branch
You can request reviews from your peers here, and your changes are then reviewed. Comments and/or suggestions may be left for the author to action, or the PR accepted if no changes required.

### 4. Address feedback, if PR is accepted perform merge
Suggestions can be accepted in the browser or applied locally then pushed up to the same branch (if accepting changes in the browser remember these will need to be pulled down from the repo to your local environment).

If all changes are acceptable then the merge can be performed!

### 5. Fetch and pull down latest changes from repo
Now that there is new content in the repo that will not exist for locally in the `main` branch, it must be fetched. Switch to this branch (if not already on it) and run
```
git fetch origin/main
```
to see if any changes are present, then
```
git pull
```
to get them.

### 6. Students who have unpublished lists, create a new branch and update this new content with your suggestions
Now we have the latest changes, we are going to add some more. Follow steps 2 & 3, resolving merge conflicts as we go (this can be done in the browser, but is best only done for very simple changes. For anything else it is better to do this in your IDE).
