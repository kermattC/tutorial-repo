# tutorial-repo
Just the basics of git. In this README it'll outline the basics of pushing your lab to github.

## Prerequisites:
1. If you haven't already, install git. Here's a link that outlines how to install git across multiple operating systems: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

## Terminal Method (Windows command prompt, MacOS/Linux terminal, etc):
1. Create a folder. Then in your terminal, change directory to that folder
2. Make sure you're in that folder. Then initialize the folder as a git repository via ```git init```
3. Copy the https link to the repository. You can find it on the main page of your repository. Click on the green button on the right that says "Code" and copy the link. It should end with ".git"
4. Clone or pull the repo. _Either way works for the case of the lab, but I highly encourage you to look up the difference between the two since you'll probably be using git for your group projects._ To clone the repo, use ```git clone <your repo link here>```. For example in this repo, I would type this in the command line: ``` git clone https://github.com/kermattC/tutorial-repo.git ```. And for pull: ```git pull https://github.com/kermattC/tutorial-repo.git``

5. You can now make changes to the files you've cloned/pulled from the repository.

6. Add the files you've made changes to. You can add them individually using ```git add <file or folder name here>```. You can use ```git add .``` to add all the files and folders that have your local changes too. 
7. Stage your changes. You can do so via ```git commit```, which will launch a text editor. You should put a message that briefly describes the changes you made, so you can refer back to it in the future. A shortcut is to do ```git commit -m "describe your changes here" ``` where you can put the commit message in the same line
8. Push your changes. Now that you're ready to upload, you can do so using the git push command. You can add a tracking reference by adding  ```-u``` at the end. You should also specify the origin and the branch you're pushing to -> ```git push -u origin <branch you're pushing to>```. \
9. Add your username and password. You'll need to sign into your github account in order to push. You can sign in using the window that pops up. Another way is to exit that window, and the CLI should direct you to enter your username. You'll need to enter your github username, then for the password you need to enter a **Personal Access Token**. This is NOT the same as your github account password. If you need help finding out how to create a personal access token, go to this link: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token


It is highly encouraged to look up what these commands do and why it is done.

## GUI Method
1. Intall GUI. Here's a link containing many choices of github gui: https://git-scm.com/downloads/guis/. I'll be using Github Desktop for Windows
2. Sign into Github.com and authorize
3. Make sure you have the correct email. You can select "Use my GitHub account name and email address" to autoamtically select your email.
4. Click on "Clone a repository from the Internet..."
5. You should have a list of repos available for you to clone. Just type in the search bar for your repo, select it and clone.

6. You can now make changes to the files you've cloned/pulled from the repository.

7. Stage changes. Any changes you've made should automatically appear in the gui. You can add the description of your changes in the bottom left. When ready, click on "Commit to main".
8. Push changes. Click on "Push origin" and your changes will be uploaded.
