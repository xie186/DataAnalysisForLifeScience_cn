# Chinese Version of the Book *Data Analysis for the Life Sciences*

## How to contribute as a collaborator

1) [Fork the repo](https://help.github.com/articles/fork-a-repo/). 

2) Go to http://198.211.107.37:8787, type you user name (same as your github account) and password. 

Go to terminal: 

```
cd /mnt/volume-nyc1-02/
mkdir USRNAME ## if it's your first time using this.
cd USRNAME
git clone https://github.com/USRNAME/DataAnalysisForLifeScience_cn.git

## Configure Git to sync your fork with the original 
git remote add upstream https://github.com/xie186/DataAnalysisForLifeScience_cn.git

## Fetch the branches and their respective commits from the upstream repository. Commits to master will be stored in a local branch, upstream/master.
git fetch upstream
git checkout master  ## Check out your fork's local master branch.

# Merge the changes from upstream/master into your local master branch
git merge upstream/master 
```

3) 
