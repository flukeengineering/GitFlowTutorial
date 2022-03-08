# How to use git flow
step 1

git clone <GIT URL>
cd <DIRRECTORY>

 
step 2 checkout development and check branch

git checkout development
checking branch
git branch

output
git branch
* development
  master

 
step 3 init gitflow

git flow init
output

 git flow init

Which branch should be used for bringing forth production releases?
   - development
   - master
Branch name for production releases: [main] main

Which branch should be used for integration of the "next release"?
   - development
Branch name for "next release" development: [development] development

How to name your supporting branch prefixes?
Feature branches? [feature/] 
Bugfix branches? [bugfix/] 
Release branches? [release/] 
Hotfix branches? [hotfix/] 
Support branches? [support/] 
Version tag prefix? [] 
Hooks and filters directory?  


step 4 start feature
git flow feature start <BACKLOG_ID>-<TASKNAME>


step 5  do anything and regular commit
 

step 6 when you want to push to GIT you can use
git flow feature publish <BACKLOG_ID>-<TASKNAME>
 

step 7 when you finish flow
git flow feature finish <BACKLOG_ID>-<TASKNAME>
 

step 8 pull and push to development
git pull
git push
