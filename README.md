1. Download Git:
	https://git-scm.com/downloads
2. Create a personal access token from Github:  
	https://github.com/settings/tokens/new  
	![](assets/README/README_image_1.png)  
	| Copy and store the token in a safe place.  
3. Open **Git Bash** and clone repository:
	 `cd Desktop`
	 `git clone https://<PERSONAL_ACCESS_TOKEN>@github.com/<USERNAME>/<REPO>.git`
	- For example:
		`git clone https://ghp_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX@github.com/3fok/StartNewVault.git`
4.  Create a new repository:  
	![](assets/README/README_image_2.png)
5. Change remote URL: Change the remote URL of the repository on your computer to point to the new repository.
	`cd <cloned_repository_directory>`
	`git remote set-url origin https://<PERSONAL_ACCESS_TOKEN>@github.com/<USERNAME>/<REPO>.git`
	`git push -u origin main`
1. Open folder as vault:  
	![](assets/README/README_image_3.png)
	- Select the cloned folder.
7. Setting Obsidian Git:
	- Commit Author: (type user name and email of github account)  
		![](assets/README/README_image_4.png)
8. Make edits to your notes
9. Publish your notes run the command "`Obsidian Git: Create backup`" by opening the command palette (`CMD/Ctrl + P`)