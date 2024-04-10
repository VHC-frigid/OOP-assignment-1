# OOP assignment 1 Part 2 Questions 

1. List three major version control software for software engineering:

* Git
* Mercurial
* Apache Subversion
2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.
 
- The biggest advantages of have to do with it's branch and merging technology which really encourages good work flow and parallel development. 

3. Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge:
- Branch - A branch represents an independent line of development.
- Pull - The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.
- Push - The git push command is used to upload local repository content to a remote repository.
- Repository - A repository is the most basic element of GitHub. It's a place where you can store your code, your files, and each file's revision history. 
- Working copy - For Git, "working copy" is a directory full of files with a . git subdirectory.
- Merge - Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch.

4. If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
- If your working in a company some polices migth include copyright when it comes to ownership of code, Data Security your governess of secure informaton and the police of the version conntrol your usinng and if it workes with your own policy of your company.

5. Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
- With tools to help with merge conflicts you can use software like git that marks conflictinng areas and you have websites like github that havebuilt-in merge conflict resolution tools.

6. In a merged source code file, how does Git let you know there is a conflict?
- git lets you know by giving you these marker's that and 2 versions of the code looking something like this:
   <<<<<<< HEAD
// Changes from the current branch (HEAD)
=======
// Changes from the other branch
//>>>>>>> branch-name

7. What are the steps you can take to resolve Git conflicts?
- Between the bottom and top 7 greater and less then sybmols you will see your merge conflict and you essiantly have to get rid of one to fix the issue

8. What does git revert do, and how can you use it?
- Git revert essiantly removes your last commit you did but keeps the history of the revert incase there was code in there you liked. And to revert you all you have to do is for example open git and type "git revert < the name of commit >" the commit you want to revert can be anyvalid Git reference that identifies the commit you want to revert.

9.What does git reset do, and how can you use it? 
- Git reset allows you to well reset any work or branches basically anything you have commited even the head but be warned this is irreversible! you cannot get back what you reset like you did with revert it can be done with the "git reset < the name of commit >" < commit > can be a commit hash, a branch name, or any other valid Git reference.

10.	What is the difference between git revert and git reset?
- Revet allows you to revet to a previous commit an reset is just thanos snapping all your shit away.

11.	True or False: It is okay to commit broken code to the main branch.
- False i am stupid and i wouldn't even do this your just asking for future merge conflicts or fights with people that want your code.

12.	True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
- true it usually makes it more understandable and review more efficiently.

13.	Describe what is DevOps, how is it useful for game developers?
- DevOps in game development typically takes advantage of cloud storage and computing to improve communication and collaboration among team members.

14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
- Ansible: Ansible is a suite of software tools that enables infrastructure as code. It is open-source and the suite includes software provisioning, configuration management, and application deployment functionality.
- Git: Git is a distributed version control system that tracks changes in any set of computer files, usually used for coordinating work among programmers who are collaboratively developing source code during software development.
- GitHub: GitHub is a proprietary platform that's owned by Microsoft. It's one of the most popular Git hosting services and is widely used for open-source projects. It offers a range of features, including code review, issue tracking, and team collaboration tools and can be used with Git.

15. What is CI/CD and how can it be used to automate the game development process?  
- CI and CD stand for continuous integration and continuous delivery/continuous deployment there methodologies that allow teams to automate and streamline software development delivery pipelines and increase the speed of development and in the end have a more high-quality software.
