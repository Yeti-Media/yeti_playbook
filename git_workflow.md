# git
* Each time that a developer starts a new task, pull orgin master and make a branch from master.
* When a task is done, the developer should rebase with master (make sure you have the latest master) and push their branch to the remote repo (e.g github).
* The developer should create a PR including the a link to the issue in the description and comments or screenshots/videos if necessary.
* The code is reviewed and commented if is needed.
* The PR is approved and merged or rejected.

#### When `submitting a PR` please check to see if you have a `conflict` and resolve it before submitting.

### Git workflow:
* Switch to your master branch

      git checkout master
      
* Sync your master with remote master

      git pull origin master
      
* Create a new task branch, when beginning a task:

      git checkout -b <my-branch-name>

(name the branch something that makes sense for the task like "mc_adding_kitchen_sink"

* To add the new and changed files:

      git add <filename or dirname>
      git commit -m "a descriptive message"

* To push the changes to the repo server:
      
      git fetch
      git rebase origin/master
      git push origin my-branch-name -f
      
* Extra help if your having trouble getting the latest master

      git checkout master
      git pull origin master  
      git checkout <my-branch-name>
      git rebase origin/master
