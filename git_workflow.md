# git
* Each time that a developer starts a new task, pull orgin master and make a branch from master.
* When a task is done, the developer should push the branch to the remote github.
* The developer should create a PR including the link to the task in the description, comments, screenshots/videos.
* The code is reviewed and commented if is needed.
* The PR is approved and merged or rejected.

### For new git users:
* To create a new task branch, when beginning a task:

      git checkout -b my-branch-name

(name the branch something that makes sense for the task like "mc_adding_kitchen_sink"

* To add the new and changed files:

    git add <filename or dirname>
    git commit -m "a descriptive message"

* To push the changes to the repo server:

    git push origin my-branch-name
