---
title: How to use Github to collaborate on Obsidian privately
tags: knowledgemanagement
toc: false
season: winter
---

1. Create a Github Account (eg. MyGithubsUserName) - this will be shared among your collaborators
2. Create a Private Repository (eg. MyFolderFor_Obsidian)
3. On your local machine open the terminal to the folder where you want to store the notes
	1.	[you can find instructions here](https://www.groovypost.com/howto/open-command-window-terminal-window-specific-folder-windows-mac-linux/#:~:text=Go%20to%20the%20folder%20you,directly%20to%20the%20selected%20folder)
4. Once the terminal is open type in git clone https://MyUserName:MyPasswordfortheaccount@github.com/MyUserName/MyFolderFor_Obsidian.git replace the placeholders i have put with your username password and foldername in github
5. Install [Github Desktop](https://desktop.github.com)- only available for Windows and Mac. The other way to do this is through the terminal which I haven't figured out yet
6. Open Obsidian (assuming you have installed it already) - on the left hand bar there should be a "Open a New Vault"
7. There choose "Open folder as Vault" and choose the folder from step 3. This should Create a new folder for notes you want to collaborate on. Just for testing purposes create a new note
8. Open and login to Github Desktop. When it asks to add a repository. Choose "Add an existing Repository" and go to the folder from step 3
9. On the left side you should see the new file you created come up as changes
10. On the top you'll see "Fetch Origin" click that to pull any changes that other have made to the github repository. Do that.
11. If you are satisfied with the changes - On the left you'll see "commit to main". click that with the necessary comments
### the problem
with this method is that two people cannot work on the same file together. to solve this
12. On Github Desktop, you'll see an option called current branch, open that and create a new branch under your name - this is the branch you will always commit to. it creates a different version of the vault
13. I'm not sure what a good time to merge is- but i'm hoping that once you look at main and see that there are no new changes to that particular file you have made, you can merge yournamebranch into main
14. for merging you can see an option under "Current Branch"