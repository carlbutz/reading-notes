# Version Control

In the readings for today we read about _version control_. There are three different types of version control: Local, Centeralized, and Distributed. Local does version control on your local machine. Centeralized does version control on a remote computer. This will allow multiple people to share the many versions when working together. Distrubuted is similar to centeralized, except it is mirrored (copied) to multiple computers. This will protect the code if there is a catastrophic failure at one of the servers. 

# What is git?

Git is a distributed version control tool. It allows snapshots to be made so a programmer can go back to a previous version if there is a need. Files in git are in one of three stages:
1. Committed => file is stored in the database
2. Modified => file has been changed, and not committed to the database
3. Staged => file is flagged to be committed, but not committed yet

# Set Up and Cloning
There is a section in today's reading to help get git set up on your local computer. This was done in last session.
There is a section in today's reading, this was also covered in a previous section.

# Workflow
There is a local repository structure that aids in managing files. The _working directory_ is where the actual files reside. The _index_ is used during staging. And the _head_ points to the most recent commit.

Another part of workflow is the life cycle. When a file is edited, it is then set in the stage area to be committed. When you are ready you commit the changes.

You can use _git status_ to see what status your files are in.

git add _< file >_ to set the file up to be committed.

git commit -m 'message' will commit the file with the coding comments found in the 'message' text.

Then to get the file from your local maching to github, you enter the git push  origin master command, and the file will be sent to github.

[Back to README](/README.md)
