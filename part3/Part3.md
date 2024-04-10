# OOP-assignment-1

### 1. Instruction to installing 

1. The system requirements: you need a version of windows 7 or higher macOS 10.9 or newer or is your on linux most Linux distributions, including Ubuntu, Fedora, Debian, and others. Ensure that your distribution is up-to-date and supports the latest Git version.
And in terms of specs if you can use paint or internet explorer your golden.

2. 
- Windows: Just go to https://git-scm.com/download/win and the download will start automatically. Note that this is a project called Git for Windows.
- Linux: i will link you to this since if you have linus in the first place you already know how to do this https://git-scm.com/download/linux.
- Mac: https://git-scm.com/download/linux install from this link and follow the installer.

3. If your having trouble installing this onto your computer you can either contact me on 0411037713 or you can contact it through reciption. 

### 2. principles/techniques of industry standard best practices creating and working with repositories and branches in Git. 

A. List the most important principles/techniques for creating and working with repositories
- Write the smallest amount of code possible to solve a problem. Committing code in small batches decreases the likelihood of integration conflicts, because the longer a branch lives separated from the main branch or codeline, the longer other developers are merging changes to the main branch, so integration conflicts will likely arise when merging. 
- Related to making small changes, atomic commits are a single unit of work, involving only one task or one fix (e.g. upgrade, bug fix, refactor). Atomic commits make code reviews faster and reverts easier, since they can be applied or reverted without any unintended side effects.
  The goal of atomic commits isn't to create hundreds of commits but to group commits by context.
- Using branches, software development teams can make changes without affecting the main codeline. The running history of changes are tracked in a branch, and when the code is ready, it's merged into the main branch.
  Branching organizes development and separates work in progress from stable, tested code in the main branch. Developing in branches ensures that bugs and vulnerabilities don't work their way into the source code and impact users, since testing and finding those in a branch is easier.
- Descriptive commit messages are as important as a change itself. Write descriptive commit messages starting with a verb in present tense in imperative mood to indicate the purpose of each commit in a clear and concise manner. Each commit should only have a single purpose explained in detail in the commit message.
  Writing commit messages in this way forces software teams to understand the value an add or fix makes to the existing code line. 
- Requesting feedback from others is an excellent way to ensure code quality. Code reviews are an effective method to identify whether a proposal solves a problem in the most effective way possible.
- Requesting feedback from others is an excellent way to ensure code quality. Code reviews are an effective method to identify whether a proposal solves a problem in the most effective way possible.

B. List the most important principles/techniques for creating and working with branches



- Centralized workflow: Teams use only a single repository and commit directly to the main branch.

- Feature branching: Teams use a new branch for each feature and don't commit directly to the main branch.

- GitFlow: An extreme version of feature branching in which development occurs on the develop branch, moves to a release branch, and merges into the main branch.

- Personal branching: Similar to feature branching, but rather than develop on a branch per feature, it's per developer. Every user merges to the main branch when they complete their work.

### 3. steps in a Git workflow that the team should follow when working on projects.

1. Initialize the central repository.
2. Hosted central repositories. Central repositories are often created through 3rd party Git hosting services like Bitbucket Cloud.
3. Clone the central repository.
4. Make changes and commit.
5. Push new commits to central repository.
6. Managing conflicts.









