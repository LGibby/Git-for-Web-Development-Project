# Git for Web Development Project
In this project you will be using the concepts learned in the Git for Web Development lesson to fork/clone/push/and submit a PR for each project during this sprint.

This project consists of two parts:

## Part One:
You will need to follow the Lambda School Git Workflow to add a file to this project follow the steps below:

- [ ] Create your own version of this repo - Fork
- [ ] Add your PM as a collaborator
- [ ] Clone this repo
- [ ] Create a branch `git checkout -b 'firstName-lastName'`
  - [ ] Add a file to the project called `yourFirstName-yourLastName`.txt. This file can contain anything.
  - [ ] Run your usual git commands for adding/commiting and pushing **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [ ] Add your PM as a reviewer on the Pull-Request
- [ ] PM then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Part Two:
Go back and follow the same steps for your [UI-III-Flexbox project](https://github.com/LambdaSchool/UI-III-Flexbox) and your [User Interface - Great Idea Project](https://github.com/LambdaSchool/User-Interface).

In order to do this, you **do not** need to create new forks of these projects. Follow the steps below for each project:

- [ ] Add your PM as a collaborator to your fork. 
- [ ] Go into your project folder, make a new branch `firstname-lastname`
- [ ] Add your first and last name to the README.md file in the project and save.
- [ ] add/commit/and push to your own branch  **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [ ] Add your PM as a reviewer on the Pull-Request
- [ ] PM then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Stretch
- [ ] While the processes learned here will set you up to be successful in most situations, they are just the tip of the iceberg in learning Git. Independantly research the following topics to learn more about Git.

		- Research and understand what a merge conflict is and how to resolve it.
		
		-  Research the Git commands
			§ pull - fetch from and integrate with another repository or local branch(according to https://git-scm.com/docs/git-pull). The pull command incorporates changes from a remote repository into the curent branch that you're working on, git pull = git fetch/git merge FETCH_HEAD. The pull command as a shorthand functions in two ways: it calls git merge to merge the retrieved branch heads into the current branch.
			§ rebase - https://git-scm.com/docs/git-rebase - The documentation is a little bit muddy to understand here. 
			§ merge - git merge joins two or more development histories together(that's why I said branching is complicated in my notes, you can have a bunch of parallel branches, here: https://git-scm.com/docs/git-merge) 
				□ These commands will allow you to bring in changes that other developers push to the master branch.
		○  Reseach the Git commands 
			§ reset - https://git-scm.com/docs/git-reset - this sounds a lot like a system restore checkpoint.
			§ revert -  https://git-scm.com/docs/git-revert - hallelujiah revert sounds awesome, it's an undo button and it can also replace the oopsie with a meaningful edit.
			§ clean. - https://git-scm.com/docs/git-clean - like comet on a porcelain tub, you can say in terminal git clean [-d] [-f] [-i] [-n] [-q] [-e <pattern>] [-x | -X] [--] <path>, -d removes untracked files/directories(like the paper scraps after we cut the snowflakes), -f is like comet and kaboom, -i is like that nice dentist who talks to you about what she's doing in your mouth, -n is please show me what you're going to do because I don't trust your crazy OCD cleaning style, -q is the maid, she doesn't bother you in your study unless something is terribly wrong, -exclude pattern (what do we mean by pattern and why would we exclude it? I don't quite understand this one), -x sounds complicated, as in it's for people who have had at least six months of continuous practice with Git, -X remove the gitignore?
				□ These commands will allow you to go back and ammends previous commits you have made.
				
	•  Research and set up a Graphical User Interface (GUI) Git console. - https://git-scm.com/book/en/v2/Appendix-A%3A-Git-in-Other-Environments-Graphical-Interfaces - so, if I CD into my desired area I can type git gui in terminal and this eye friendly window will pop open?
	
	•  Research and setup SSH keys with Github, so that you do not need to input your username/password each time you push. - I don't remember how I did this, but, yes I was prompted to login (or maybe I looked it up in the docs and used the help file to figure out how to login?) but no I don't have to login every time I open Git Bash.


