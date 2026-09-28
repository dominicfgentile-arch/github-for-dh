# GitHub for Digital Humanities
Presented by: Olivia Olson and Dominic Gentile
# Step-by-step Instructions
## Find the GitHub Repository and Documentation
Go to the github-for-dh repository online, [https://github.com/dominicfgentile-arch/github-for-dh](https://github.com/dominicfgentile-arch/github-for-dh). Keep it open in your browser throughout the workshop. Use the README on the homepage for reference.

## Install Git

### Installing Git on Windows machines

Use the command line:

1) In Powershell copy this command `winget install --id Git.Git -e --source winget`
2) Paste it into Powershell using ctrl + C
3) Press enter
4) This will take you to a dialog box that will walk you through the installation.
5) Click through the installation without changing any of the options.

Use the GUI installer:

1) Navigate to [https://git-scm.com/install/windows](https://git-scm.com/install/windows)
2) Select “Click here to download” at the top of the page
3) This will take you to a dialog box that will walk you through the installation.
4) Click through the installation without changing any of the options.

### Installing Git on Macs

1) In terminal type `xcode-select --install` + return
2) Paste it into Terminal using cmd + C
3) Press enter
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
**Type `pwd` + enter/return** to determine where you are on your computer (aka your **current working directory**). Your terminal should output something like this: `/c/Users/<Username>`.  This is called a **filepath**. 

Your desktop is located here: `/c/Users/<Username>/desktop`.  By adding `/desktop` we are telling the computer to move to your desktop folder which is located within \<Username>\.

To get to your desktop we use `cd <filepath>`. `cd` **c**hanges our **d**irectory from one file path to another. 

**Type `cd ~/desktop` + enter/return.**

**Test where you are using `pwd`.**

## List the Files on Your Desktop using `ls`
**Type `ls` + enter/return** after you have moved to your desktop to see all of your files and directories contained there.

## Clone our GitHub Repository using `git clone <url>.git`
**Type `clone git https://github.com/dominicfgentile-arch/github-for-dh.git` + enter/return**

Check to see the contents of this repository using `ls`

# Command Line Reference

## Git Commands

| Process         | Description                                                                                                                   |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| init            | creates a new repository                                                                                                      |
| clone <url>.git | used to download a local copy of a remote repository. Use only once.                                                          |
| pull            | used to update the local copy of the repository with changes (“commits”) that other users have made to the remote repository. |
| commit          | logs the changes you made to your local repository                                                                            |
| push            | takes local changes (created, edited, deleted files) and adds them to the remote repository                                   |

![An image displaying the standard Git workflow.](media/adhikari_github_workflow.png)

Adhikari, Sujan. (2023, November 20). How Git works: A visual guide with code. Medium.


## Powershell/Terminal Commands

| Command                | Description                                                                                                                                                                                |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| cd <filepath>          | change current directory – change the folder in which your commands will work  <br>  <br>Use “cd ~” to navigate to your home directory  <br>And “cd ~/desktop” to navigate to your desktop |
| pwd                    | print working directory – prints out the filepath of the directory you are currently in                                                                                                    |
| ls                     | lists the files and directories contained in your current working directory                                                                                                                |
| git --version          | Use to check to see if you have Git installed or which version of git you have                                                                                                             |
| git --clone <url>.git  | Use to download a local copy of a remote repository. Use only once.                                                                                                                        |
| clear                  | Clears your terminal window.                                                                                                                                                               |
| ctrl + c (control + c) | Quits a process that is running.                                                                                                                                                           |


Use `git clone` in place of `git fetch` the first time you download the remote repository

# References

“1.3 Getting started - What is Git?” (n.d.). Git. Accessed September 20, 2026. [https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)

Adhikari, Sujan. (2023, November 20). How Git works: A visual guide with code. *Medium*. [https://medium.com/@sujanaddy98/how-git-works-a-visual-guide-with-code-b4edf2694298](https://medium.com/@sujanaddy98/how-git-works-a-visual-guide-with-code-b4edf2694298)

Becker, D., Williamson, E., & Wikle, O. (2020). CollectionBuilder-CONTENTdm: Developing a static web ‘skin’ for CONTENTdm-based digital collections. *Code{4}lib Journal, 49*. [https://journal.code4lib.org/articles/15326](https://journal.code4lib.org/articles/15326) 

“Branches.” (2026). [https://docs.github.com/en/pull-requests/reference/branches](https://docs.github.com/en/pull-requests/reference/branches) 

Craig, K., Dalmau, M., & Purcell, S. (2026, March 25). Operationalizing minimal computing values through shared computing-platform development: A case study of DigitalArc and Opaque Publisher.  *In the Library with the Lead Pipe*. [https://www.inthelibrarywiththeleadpipe.org/2026/digitalarc/](https://www.inthelibrarywiththeleadpipe.org/2026/digitalarc/) 

ghostinhershell. (2025, July 25). “Day 1: What is GitHub (and why do people use it)? 🤔.” GitHub. [https://github.com/orgs/community/discussions/167863](https://github.com/orgs/community/discussions/167863)

Koeser, R.S., Budak, N. (2025). mep-django \[Computer software]\. [https://github.com/Princeton-CDH/mep-django](https://github.com/Princeton-CDH/mep-django)

Kotin, J., Koeser, R.S. et al. “Discoveries.” (2021). Shakespeare and Company Project, version 1.10.1. Center for Digital Humanities, Princeton University. [https://shakespeareandco.princeton.edu/discoveries/](https://shakespeareandco.princeton.edu/discoveries/)

Kotin, J., Koeser, R.S. et al. (2025). Shakespeare and company project, version 1.10.1. Center for Digital Humanities, Princeton University. [https://shakespeareandco.princeton.edu/](https://shakespeareandco.princeton.edu/)

“Pull Requests.” (2026). [https://docs.github.com/en/pull-requests/reference/pull-requests](https://docs.github.com/en/pull-requests/reference/pull-requests)

# Resources

“Bash Tutorial.” (2026). W3Schools. [https://www.w3schools.com/bash/index.php](https://www.w3schools.com/bash/index.php)

"Difference between terminal, console, shell, and command line." (2025, July 23). GeeksforGeeks. [https://www.geeksforgeeks.org/operating-systems/difference-between-terminal-console-shell-and-command-line/)](https://www.geeksforgeeks.org/operating-systems/difference-between-terminal-console-shell-and-command-line/)

“Git Cheat Sheet.” (n.d.). Git. Accessed September 20, 2026. https://git-scm.com/cheat-sheet

“GitHub Student Developer Pack.” GitHub. [https://education.github.com/pack](https://education.github.com/pack)
- Microcredentials and short courses
- Access to learning modules and certifications that are usually paywalled
- Free access upon proof that you are a student

“Software Carpentry Lessons.” (2026). Software Carpentry. The Carpentries. [https://software-carpentry.org/lessons/](https://software-carpentry.org/lessons/)
- See ["The Unix Shell"](https://swcarpentry.github.io/shell-novice/) and ["Version control with Git"](https://swcarpentry.github.io/git-novice/) lessons
