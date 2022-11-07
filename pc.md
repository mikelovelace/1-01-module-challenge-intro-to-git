## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?\
    Git is a version control system used by developers that tracks and keeps a history of changes done to code/files, which
    are stored in a local repository on their computer.

2. What is the difference between Git and GitHub?\
    Git is a version control system that tracks changes in a persons local files/code and saves those changes through commits.
    Each commit is like a snapshot of changes that are stored for later access. 
    This allows one to have multiple versions of files/code which can be reverted to should something bad happen.
    I.E deleted files, broken code etc.

    Github is a service to store copies of local files/code into a remote repository.
    This allows developers to have access to other developers projects by cloning the repository to their computer 
    and using git to commit changes on a seperate branch which can then be merged into the main branch after being approved.

3. Why do we create a branch?\
    We create branches so any changes made to the source code only affect a specific branch.
    This allows a developer to make sure any changes made to the source code don't cause any 
    issues before merging the changes from that branch into the main code branch.

4. What is the purpose of a Pull Request?\
    The purpose of a pull request is to allow any changes made to a project to be reviewed and approved before
    being merged into the main code's repository, which prevents issues from arrising.
    I.E. Broken Code

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.\
    git checkout branch-name

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?\

7. What is a merge conflict?\

8. How do you resolve a merge conflict?\
