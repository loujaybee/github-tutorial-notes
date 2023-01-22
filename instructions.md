### Why Git? What is Git?

* `git` command-line tool `github` the company 
* `git` is the open-source library (found here: https://github.com/git/git)
* Around ~75% of companies use GitHub + Git is primary VCS
* Alternatives to Git + GitHub: SVN, Gerrit, AWS CodeCommit
* Benefits of Git + GitHub? Why do companies use it? 
  * "Return to a previous version of an application"
  * Branches, Pull Request (GitHub), Commits ("Save"), Tags (Version)
  * Many commits in a branch
* "Branch Strategy"
  * [GitHub Flow](https://i0.wp.com/lanziani.com/slides/gitflow/images/gitflow_1.png)
  * [Basic Flow](https://littlekendra.com/images/release-flow.png)
 
### Who needs to know Git?

**Should know (uses git day-to-day)**
* DevOps
* Cloud Engineers
* Software Engineers (front-end, back-end)

**Nice to have (not using day-to-day)**
* Solutions Architect
* Cloud Support

### Main things to know

* `git status` => Tells us whats going on with our code local copy.
* `git add file.txt` => Tells git to track the file, prepares it to be committed.
* `git commit -m "My first file committed"` => "Saves your changes"
* `git push` => Syncs your local copy with GitHub (if you don't do this, and your laptop falls in a lake, your code is lost forever)
* `git push --set-upstream origin garcia-adding-search-feature` => Creates a copy of the branch in GitHub. 

**A "full flow"**

1. `git add file.txt` => Tells git to prepare to be committed
2. `git commit -m "a message"` => Saves the change
3. `git push` => Syncs the change with GitHub

### Things to practice

1. Create a repo (e.g. a website)
2. Create a branch (e.g. `task-1`)
3. Add files, modify files, delete files
4. Commit changes
5. Push changes
6. Raise pull requests, merge pull requests

**Take the following scenario:** 
* You are an employee asked to "make a website for clothing". 
* Go and create the clothing website repo. 
* You are given a first task to create a "homepage". 
* Create a branch for your new task and add a "homepage.txt". 
* Push the changes and open a pull request. 
* Comment your own pull request as your "colleague", who asks you to add an image to the homepage.
* Add a file "image.txt" and update the "homepage.txt" content. 
* Commit and push this change. 
* Review your pull request. 
* Approve the pull request. 
* Merge the pull request. 
 
Repeat the above until you feel more comfortable! 
