# GIT CONTRIBUTION PROTOCOL
By [Jeremy Deschamps](https://jddev.net)

## Description

A simple git contribution protocol

## Get code

- FIRST TIME ONLY : download the `staging` branch :
```
git clone -b staging https://__PROJECT_URL__.git
cd __PROJECT_NAME__
```

- NEXT TIME ONLY : pull the `staging` branch :
```
git checkout staging
git pull
```

## Create a branch

- Create a new branch to work on, please use an explicit name (exemple: use the issue number and camelCase name) :
```
git checkout -b __MY_BRANCH_NAME__
```

## Work

- Make your job ...

## Commit

- Please use this syntax for commit :
```
Fix : My short description to correct something
Up : My short description to upgrade something
Add : My short description to add something
Rem : My short description to remove something
```

- When the job is finish, commit :
```
git add .
git commit -m "Fix : __MY_EXAMPLE_COMMIT__"
```

## Push

- Push on repo :
```
git push https://__PROJECT_URL__.git
```

## Ask a Pull request on Master

- Ask a Merge request on the online repo go to your branch and click on `Compare and pull request` select the base branch `staging `and valid your request

## Merge (only for authorized users)

- Inside the online repo and on your branch, click on `Pull request` and merge your branch to the `staging`, next go to the branchs list and delete your branch