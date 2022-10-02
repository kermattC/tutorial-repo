# tutorial-repo
Just the basics of git. In this README it'll outline the basics of pushing your lab to github.

Prerequisites:
1. If you haven't already, install git -Here's a link that outlines how to install git across multiple operating systems: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

Terminal Method (Windows command prompt, MacOS/Linux terminal, etc):
1. Create a folder. Then in your terminal, change directory to that folder
2. Make sure you're in that folder. Then initialize the folder as a git repository via ```git init```
3. Copy the https link to the repository. You can find it on the main page of your repository. Click on the green button on the right that says "Code" and copy the link. It should end with ".git"
4. Clone or pull the repo. _Either way works for the case of the lab, but I highly encourage you to look up the difference between the two since you'll probably be using git for your group projects._ To clone the repo, use ```git clone <your repo link here>```. For example in this repo, I would type this in the command line: ``` git clone https://github.com/kermattC/tutorial-repo.git ```. And for pull: ```git pull https://github.com/kermattC/tutorial-repo.git```
5. By now you've got a copy of the repository. You can now make changes to it. After you're ready to push the changes, first add the files you have changed. You can add them individually using ```git add <file or folder name here>```. You can use ```git add .``` to add all the files and folders that have your local changes too. 
6. Stage your changes. You can do so via ```git commit```, which will launch a text editor. You should put a message that briefly describes the changes you made, so you can refer back to it in the future. A shortcut is to do ```git commit -m "describe your changes here" ``` where you can put the commit message in the same line
7. Push your changes. Now that you're ready to upload, you can do so via ```git push 
