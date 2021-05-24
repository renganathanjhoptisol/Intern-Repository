"# Intern-Repository" 

## Set-up environment

## Install node Js

We recommend installing Node via @Chocolatey, a popular package manager for windoows.

## To install node Js via @Chocolatey

# To copy the link and paste the powershell administrator on your system

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

## To refer Installation and React Native Documentation Using this link

https://reactnative.dev/docs/environment-setup

## Install Visual Studio Code

# Here is the link for download vs code

https://visualstudio.microsoft.com/vs/community/



## Create react-native project

## After setting-up the environment, To create a new project

# There are two type of CLI

	1. Expo CLI
	2. React Native CLI

	@The difference between Expo CLI and React Native CLI 

		Expo projects do not reveal the native ios and Android projects 
	that react-native cli does.

## First to install expo cli in your System

	> npm install -g expo cli

## Now create a project

	> expo init <projectName>

	While creating a project you have faced a issue that is 
	
	> running scripts is disabled on this system like this!!!

## How to fix this
	
	1. Start powershell in administrator mode.
	2. Type the following command "set-ExecutionPolicy RemoteSigned" @type without quotation mark on the powershell
	3. Press Y for your Confirmation.

## After that the issue is cleared.

# Then we start the project
	
	> cd <projectName>
	> npm start or expo start

 
## create git repo in the github

## Create a git repository and push your new project in the repo with proper read me file with screenshots included.

# Please refer this link about git

	1. https://www.freecodecamp.org/news/a-beginners-guide-to-git-how-to-create-your-first-github-project-c3ff53f56861/
	2. https://www.earthdatascience.org/workshops/intro-version-control-git/basic-git-commands/

## Time to start!

	1. Github Account Creation
	2. Git Installation
	
		@ For git installation Please click the link below
		https://gitforwindows.org/ - For windows 
	
	3. Verify git is installed correctly, on your system
		
		> git --version (powershell or git bash)
	4. One last step is needed to complete the installation correctly! You need to run in your terminal the following commands with
	   your information to set a default username and email when you are going to save your work:

		> git config --global user.name "<username>"

		> git config --global user.email "<email>"  !!! Note : Use your Github : "username, email" 

	5. Your first GitHub project
	
		-> Create a new Respository @Please refer the two links
	
	6. Add a local version of Your computer

## Useful Commands for git

	1. Display the history of commits (all modifications made on the project).

		> git log

	2. Revert back all your changes since the last commit.

		> git checkout

	3. Revert all changes on a specific file since the last commit.

		> git checkout [fileName]

	4. Display the last changes on a file since the last commit.

		> git diff [fileName]

	5. Remove all unexpected files in your project (not committed).

		> git clean -dfx

	6. Add all files and make a commit at the same time.

		> git commit -am [message]


	@Note: I have said some Useful commands and steps to create git and repository

	# You people please refer the link 

	@ https://www.freecodecamp.org/news/a-beginners-guide-to-git-how-to-create-your-first-github-project-c3ff53f56861/

	@ https://www.earthdatascience.org/workshops/intro-version-control-git/basic-git-commands/

## Snapshot Link
	![@output](https://user-images.githubusercontent.com/84439115/119001034-413c1400-b9a9-11eb-88ce-01dd749421d2.png)
	![@vsout](https://user-images.githubusercontent.com/84439115/119001072-49944f00-b9a9-11eb-97e4-245997e4e10f.png)
	![@bout](https://user-images.githubusercontent.com/84439115/119001082-4b5e1280-b9a9-11eb-92ff-e944e6bfaf2c.png)

