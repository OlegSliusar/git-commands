## Importand Git commands from [Learn Enough Git to Be Dangerous](https://www.learnenough.com/git-tutorial)

Command|Description|Example
:--                     |:--                                           |:--
`git help`              |Get help on a command                         |`$ git help push`
`git config`            |Configure Git                                 |`$ git config --global …`
`source <file>`         |Activate Bash changes                         |`$ source ~/.bash_profile`
`mkdir -p`              |Make intermediate directories as necessary    |`$ mkdir -p repos/website`
`git status`            |Show the status of the repository             |`$ git status`
`touch <name>`          |Create empty file                             |`$ touch foo`
`git add -A`            |Add all files or directories to staging area  |`$ git add -A`
`git add <name>`        |Add given file or directory to staging area   |`$ git add foo`
`git commit -m`         |Commit staged changes with a message          |`$ git commit -m "Add thing"`
`git commit -am`        |Stage and commit changes with a message       |`$ git commit -am "Add thing"`
`git diff`              |Show diffs between commits, branches, etc.    |`$ git diff`
`git commit --amend`    |Amend the last commit                         |`$ git commit --amend`
`git show <SHA>`        |Show diff vs. the SHA                         |`$ git show fb738e…`
`git remote add`	      |Add remote repo	                             |`$ git remote add origin`
`git push -u <loc> <br>`|Push to branch to remote	                     |`$ git push -u origin master`
`git push`	            |Push to default remote	                       |`$ git push`
`.gitignore`	          |Tell Git which things to ignore	             |`$ echo .DS_store >> .gitignore`
`git checkout <br>`	    |Check out a branch	                           |`$ git checkout master`
`git checkout -b <br>`	|Check out & create a branch	                 |`$ git checkout -b about-page`
`git branch`	          |Display local branches	                       |`$ git branch`
`git merge <br>`	      |Merge in a branch	                           |`$ git merge about-page`
`git rebase`	          |Do something possibly weird & confusing	     |See [xkcd: Git][xkcd]
`git branch -d <br>`	  |Delete branch (if merged)	                   |`$ git branch -d about-page`
`git branch -D <br>`	  |Delete branch (even if unmerged) (dangerous)	 |`$ git branch -D other-branch`
`git checkout -f`	      |Force checkout, discarding changes (dangerous)|`$ git add -A && git checkout -f`
`git clone <URL>`	      |Copy repo (incl. full history) to local disk	 |`$ git clone https://ex.co/repo.git`
`git pull`	            |Pull in changes from remote repository	       |`$ git pull`
`git branch -a`	        |List all branches	                           |`$ git branch -a`
`git checkout <br>`	    |Check out remote branch and configure for push|`$ git checkout fix-trademark`
`gh-pages`	            |Branch name for production website	           |`$ git push -u origin gh-pages`

[xkcd]: https://m.xkcd.com/1597/
