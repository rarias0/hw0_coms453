
#Is Git for you?
The main reason to use a version control system is to successfully track progress on files, directories, projects, etc. Thus, using a version control system, in our case Git, is an essential tool for working in groups and for individual projects as well. 

Git does not dictates the way you should track your projects. However, If you're a newbie, you must know that there are defined 'work models' that most people follow to increase productivity when working in groups, these models are called Git workflows. To determine what workflow you should use you will have to do your own research, since there is not a best choice by default.
Here we will name a few to give you some reference.

* [Centralized Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows)
* [Git Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)
* [Gitflow Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
* [Forking workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow) 

Here are some highlights about Git:

* The main feature about Git that most people tend to appreciate is being able to undo work or make contributions at any time without regrets. This previous statement refers to the record of logs that Git keeps whenever a directory is being tracked, and the way Git allows you to create new branches to modify/test new ideas aside. 

* Whenever you use Git the terminal should be your choice of preference. Even though SourceTree or Bit bucket may seem like good tools for git, you must now that they do not support every git command. Furthermore, using the terminal may facilitate multitasking, i.e. when testing servers using the linux command line.

* Perhaps the most important tip in this discussion is the following, always provide clear description when you create a commit, else you may waste a lot of time navigating through logs to find a particular version of your project.

Even though Git may seem like the ideal tool to trak milestones on your project, one must remember that in order to get the most out of this version controller you need to make sure that each member of the repository provides good documentation about their work; Keep in mind that your code is very likely to be reviwed by others, thus providing appropiate and chronological descriptions of an individual's work will aid others to unduestand the loginstics of the project.


####Here we provide a set of simple commands to help you start:
```
	$git config --global user.name 	"new name"
	$git config 	     user.name 	"new name for local repo"
	$git config --global user.name   		//show current		
	$git config --global user.email	"new email"
	$git config --global user.email   		//show current	

	$git init						//initialize a git repository
	$git status						//show staging area and files that are being tracked and which ones are not
	$git add						//add content from wotrking copy to the satging area. 	
	$git rm							//remove and add changes to staging area 							
	$git brach
	$git commit						//creates new commit

	$git diff						//working copy and staging area
	$git diff 	--staged			//staging area and repo
	git diff 	HEAD				//working copy and repo
	git reset 	HEAD~1				//undo last commit, staging area is empty, working copy remains
	git reset 	--hard HEAD~1		//undo last commit, staging area is empty, working copy is empty
			"	  WC empty

	$git log							//show records of logs with respective hahes and basic info
	
	
