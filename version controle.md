
**What is git?**

__answer :__

  it's a version controls tool that allow tracking all changes in group of files "repository",

=====================================================

**why using it ?**

__answer :__

  save all versions of a project so it can be reviewed again , protect changes from being lost upon time and ease of team work by allowing changes tracking to point files differences ..

=====================================================

**what version control tools did you use that is based on git ?**

__answer :__

  1. github
  2. git-cli  

=====================================================

**maybe you should know first what version control systems are ?**
__answer :__

=====================================================

**When using git, what exactly do people mean when they talk about “the SHA-1”?**

__answer :__

  for each commit, version, tag, relationships between files and directories, a unique hash will be created to point at a specific version of files at that commit so it can be refereed to as needed using that hash and will be protected from accidental and malicious changes ...  

=====================================================

**How does git rebase function compared to git merge?**

__answer :__

  rebase moves the changes with all it's commits to the target branch so all the log will be overwritten to include the new commits while merge will get all changes in files to be but as a new commit at the top of the log of the target branch .. basically rebase is more commonly used than merge but mainly merge seems to be easier to undo (friend of beginners) ...
  
=====================================================

**what's the difference between git pull and git update in GIT?**

__answer :__

***git remote update*** will update all of your branches set to track remote ones, but not mesrge any changes in.

***git pull*** will update and merge any remote changes of the current branch you're on. This would be the one you use to update a local branch.