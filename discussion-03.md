# Lesson 3 Learnings

In the first part of the lesson we learned how to clone our github repo to our local machine, how to edit the file locally, and the push the file back to github.
To do this you:

1. Goto github.com and log in
2. Be in the repo you want to clone
3. In the Green Code button use the dropdown arrow to see options
4. Click on the picture of the clipboard to copy the URL to the clipboard
5. Open Windows PowerShell
6. Start a Ubuntu session
7. Using CD, PWD and LS (all lower case, upper here for clearification) go to the project folder on your local computer
8. type git clone _and paste the URL here_

Now your repo is on your local machine. Typing git status will show the current status of you files.

Other important commands:

> code . => opens the VS editor
> git add <file> => sets the edited file ready to be commited to github
> git checkout -- <file> => removes the file from the commit staging area
> git commit -m '_message_' => commits the file with the message as comments on what took place with the file
> git push origin master => commits the file to github
