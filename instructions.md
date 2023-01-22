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

#### Adding files

* `git status` => Tells us whats going on with our code local copy.
* `git add file.txt` => Tells git to track the file, prepares it to be committed.
* `git commit -m "My first file committed"` => "Saves your changes"
* `git push` => Syncs your local copy with GitHub (if you don't do this, and your laptop falls in a lake, your code is lost forever)
* `git push --set-upstream origin garcia-adding-search-feature` => Creates a copy of the branch in GitHub. 

A "full flow"
1. `git add file.txt` => Tells git to prepare to be committed
2. `git commit -m "a message"` => Saves the change
3. `git push` => Syncs the change with GitHub

#### Other stuff

* `git status` => Your home base
* `git add temp.txt` => 
* `git add --all` // Use sparingly 
* `git commit -m "detailed commit message here"`
  * Important to leave good commit messages
* The difference between: "Untracked", staged, pushed (`.gitignore`)

### Extra stuff

* `git rebase`
* `git clone`


### Notes

* Garcia
  * Get the CCP (work on some projects)
  * 31st of January
  * Doing some online tests
  * Cloud Quest (hands on things)
  * Static website (S3 bucket)
  * Instances in EC2 (change the instance type)
* Sara
  * Do I need GitHub account?
  * 