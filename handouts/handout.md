# GitHub for Digital Humanities
Presented by: Olivia Olson and Dominic Gentile
# Step-by-step Instructions
## Find the GitHub Repository and Documentation
Go to the github-for-dh repository online, [https://github.com/dominicfgentile-arch/github-for-dh](https://github.com/dominicfgentile-arch/github-for-dh). Keep it open in your browser throughout the workshop. Use the README on the homepage for reference.

## Install Git
### Installing Git on Windows machines
Use the command line:

1) In Powershell copy this command `winget install --id Git.Git -e --source winget`
2) Paste it into Powershell using `ctrl + C`
3) Press `enter`
4) This will take you to a dialog box that will walk you through the installation.
5) Click through the installation without changing any of the options.

Use the GUI installer:

1) Navigate to [https://git-scm.com/install/windows](https://git-scm.com/install/windows)
2) Select “Click here to download” at the top of the page
3) This will take you to a dialog box that will walk you through the installation.
4) Click through the installation without changing any of the options.

### Installing Git on Macs
1) In terminal type `xcode-select --install` + return
2) Paste it into Terminal using `cmd + C`
3) Press `enter`
4) This will take you to a dialog box that will walk you through the installation.
5) Click through the installation without changing any of the options.

**In you are unable to install Git using this method please let us know!**

## Open the Command Line
Windows Users:
- Press the windows key (⊞) and enter "powershell" in the search bar + enter

Mac Users:
- Go to the Spotlight search bar and type "terminal" + return

## Verify that You Have Git Installed
**Type `git --version` into the command line.** If you get an error message you do not have Git installed or typed the command incorrectly.

If you have Git installed your terminal should output something like this: `git version 2.55.0.windows.5`

## Navigate to your Desktop Using `cd`
**Type `pwd` + `enter`/`return`** to determine where you are on your computer (aka your **current working directory**). Your terminal should output something like this: `/c/Users/<Username>`.  This is called a **filepath**. 

Your desktop is located here: `/c/Users/<Username>/desktop`.  By adding `/desktop` we are telling the computer to move to your desktop folder which is located within \<Username>\.

To get to your desktop we use `cd <filepath>`. `cd` **c**hanges our **d**irectory from one file path to another. 

**Type `cd /c/Users/<Username>/desktop` + `enter`/`return`.**

**Test where you are using `pwd`.**

## List the Files on Your Desktop using `ls`
**Type `ls` + `enter`/`return`** after you have moved to your desktop to see all of your files and directories contained there.

## Clone our GitHub Repository using `git clone <url>.git`
**Type `clone git https://github.com/dominicfgentile-arch/github-for-dh.git` + `enter`/`return`**

Check to see the contents of this repository using `ls`

# Command Line Reference
## Git Commands

| Command        | Description                                                                                                                   |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| `init`            | creates a new repository                                                                                                      |
| `clone <url>.git` | use to download a local copy of a remote repository. Use only once.                                                          |
| `pull`            | use to update the local copy of the repository with changes (“commits”) that other users have made to the remote repository. |
|  `add .`            | use when you are ready to add the files/directories from your local repository to the remote repository |
| `commit -m <message>`          | logs the changes you made to your local repository. allows you to write a quick message describing the changes made (always put in quotes)                                                                            |
| `push`            | takes local changes (created, edited, deleted files) and adds them to the remote repository                                   |

Use `git clone` in place of `git fetch` the first time you download the remote repository

<img src="https://github.com/dominicfgentile-arch/github-for-dh/blob/main/media/adhikari_github_workflow.png" width="400">


Adhikari, Sujan. (2023, November 20). How Git works: A visual guide with code. Medium.


One you have files ready to go to your remote repository enter these commands in this order: `git add .` --> `git commit -m <message>` --> `git push`


## Powershell/Terminal Commands

| Command                    | Description                                                                             |
| -------------------------- | --------------------------------------------------------------------------------------- |
| `cd <filepath>`            | change current directory – change the folder in which your commands will work           |
| `pwd`                      | print working directory – prints out the filepath of the directory you are currently in |
| `ls`                       | lists the files and directories contained in your current working directory             |
| `git --version`            | Use to check to see if you have Git installed or which version of git you have          |
| `git --clone <url>.git`    | Use to download a local copy of a remote repository. Use only once.                     |
| `clear`                    | Clears your terminal window.                                                            |
| `ctrl + c` (`control + c`) | Quits a process that is running.                                                        |
