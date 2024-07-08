## Create new Obsidian vault on Windows
1.  Create a new repository:  
	![](assets/Create%20new%20Obsidian%20vault/Create%20new%20Obsidian%20vault_image_1.png)
2. Download Git:  
	https://git-scm.com/downloads
3. Create a personal access token from Github:  
	https://github.com/settings/tokens/new  
	![](assets/Create%20new%20Obsidian%20vault/Create%20new%20Obsidian%20vault_image_2.png)
	| Copy and store the token in a safe place.
4. Open **Git Bash** and clone repository:
	 `cd Desktop`
	 `git clone https://<PERSONAL_ACCESS_TOKEN>@github.com/<USERNAME>/<REPO>.git`
	- For example:
		`git clone https://ghp_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX@github.com/3fok/ObsiNote.git`
	- Move to cloned folder:
		`cd ObsiNote/`
	- Create a new repository on the command line:
		`echo "# ObsiNote" >> README.md`
		`git init`
		`git add README.md`
		`git commit -m "first commit"`
		`git branch -M main`
		`git push -u origin main`
5. Open folder as vault:  
	![](assets/Create%20new%20Obsidian%20vault/Create%20new%20Obsidian%20vault_image_3.png)
	- Select the cloned folder.
6. Install the Obsidian Git community plugin
	- Turn on community plugins  
		![](assets/Create%20new%20Obsidian%20vault/Create%20new%20Obsidian%20vault_image_4.png)
	- Install:  
		![](assets/Create%20new%20Obsidian%20vault/Create%20new%20Obsidian%20vault_image_5.png)
		![](assets/Create%20new%20Obsidian%20vault/Create%20new%20Obsidian%20vault_image_6.png)
		![](assets/Create%20new%20Obsidian%20vault/Create%20new%20Obsidian%20vault_image_7.png)
7. Setting Obsidian Git:
	- Commit Author: (type user name and email of github account)  
		![](assets/Create%20new%20Obsidian%20vault/Create%20new%20Obsidian%20vault_image_8.png)
	- Pull updates on startup:  
		![](assets/Create%20new%20Obsidian%20vault/Create%20new%20Obsidian%20vault_image_9.png)
8. Make edits to your notes
9. Publish your notes run the command "Obsidian Git: Create backup" by opening the command palette (CMD/Ctrl + P)


## Setting up on another PC
1. Download Git:
	https://git-scm.com/downloads
2. Open **Git Bash** and clone repository:
	 `cd Desktop`
	 `git clone https://<PERSONAL_ACCESS_TOKEN>@github.com/<USERNAME>/<REPO>.git`
	- For example:
		`git clone https://ghp_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX@github.com/3fok/ObsiNote.git`
3. Open folder as vault:  
	![](assets/Create%20new%20Obsidian%20vault/Create%20new%20Obsidian%20vault_image_10.png)
	- Select the cloned folder.
4. Setting Obsidian Git:
	- Commit Author: (type user name and email of github account)  
		![](assets/Create%20new%20Obsidian%20vault/Create%20new%20Obsidian%20vault_image_11.png)
5. Make edits to your notes
6. Publish your notes run the command "`Obsidian Git: Create backup`" by opening the command palette (`CMD/Ctrl + P`)