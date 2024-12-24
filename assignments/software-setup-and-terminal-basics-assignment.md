# Software Setup And Terminal Basics Assignment

For this assignment, you will show that you have installed all the software specified in the computer setup file, logged into the chats and software that require a user account, and that you are able to use commands in your terminal application.

## Learning objectives

This assignment should prove that a student:

- Has all the software required for the program installed and set up.
- Can create a folder using the Terminal application.
- Can create an HTML file using the Terminal Application.
- Can initiate a project in VSCode using the Terminal application.

## Requirements

Record a Loom video following the steps described below. Each step serves as acceptance criteria, so please make sure the outcomes described for each step match what you see on your screen while recording the video.

**HINT:** Recording a Loom video with a Loom desktop client app lets you pause while recording, test the next set of instructions, and then resume recording to demonstrate the outcomes of those steps.

> You must follow EVERY step unless the step includes the OS that you are not working with.

The recorded video will prove that:

- [ ] The software is installed.
  - [ ] **For MacOS only:** Homebrew should be installed.
    1. Open the terminal application.
    2. Execute the command `brew doctor`.
    3. The output should indicate "Your system is ready to brew".
  - [ ] Google Chrome Browser app is installed.
    1. Show the app icon in your applications.
    2. Launch the application.
    3. Close the app.
  - [ ] Discord app is installed.
    1. Show the app icon in your Applications.
    2. Launch the application.
    3. Ensure you are enrolled into Devslopes Web Academy Server.
    4. The username set for the Devslopes Web Academy Server should be your first and last name.
    5. Close the app.
  - [ ] Zoom app is installed.
    1. Show the app icon in your applications.
    2. Launch the app, ensure you are signed in or sign in to your account while recording.
    3. Close the app.
  - [ ] Loom app is installed (will be automatically proved since you are going to record a Loom video).
    1. Show the app icon in your applications.
  - [ ] VSCode app is installed.
    1. Show the app icon in your applications.
    2. Launch the app.
    3. **For Windows only:** Open the Extensions sidebar. The WSL extension should be installed.
    4. Close the app.
  - [ ] **For Windows only:** WSL and Ubuntu distribution are installed.
    1. Show the Ubuntu app icon in your Applications.
    2. Run your Ubuntu distribution.
    3. The command line should load with a logged-in Unix user.
    4. Leave the app running.
  - [ ] ZSH is installed and set as the default shell.
    1. In your Terminal, execute `echo $SHELL`.
    2. Ensure the output ends with ".../zsh".
  - [ ] NVM is installed.
    1. In your Terminal, execute `nvm --version`.
    2. The output should display the version of NVM in the format 'x.y.z' or 'x.yy.z'.
  - [ ] NodeJS is installed with NVM.
    1. In your Terminal, execute `nvm ls`.
    2. At least v18.17.1 of NodeJS should be on the list of installed versions.
    3. At least v18.17.1 of NodeJS should be assigned to the alias of "default".
  - [ ] NPM is installed.
    1. In your Terminal, execute `npm -v`.
    2. The output should display the version of NPM in the format 'x.y.z'.
  - [ ] GIT is installed, git user is set.
    1. In your terminal, execute `git --version`.
    2. The output should display the git version in the format 'git version x.yy.z'.
    3. In your terminal, execute `git config user.name`.
    4. The output should display the git user's name.
    5. In your terminal, execute `git config user.email`.
    6. The output should display the git user's email.
  - [ ] SSH key is set and connected to your GitHub account.
    1. In your terminal, execute `ssh -T git@github.com`.
    2. If asked to verify the fingerprint, answer 'Yes'.
    3. The output should say: 'Hi USERNAME! You've successfully authenticated...'.
- [ ] You can use basic terminal commands.
  1. Navigate your terminal to the user's home location.
  2. List the folders and files of your user home location.
  3. List all (including hidden) the folders and files of your user's home location.
  4. Create a new folder named "Devslopes projects" in your user's home location.
  5. Navigate your terminal into that new location.
  6. Create a new folder named "demonstration-project" in the new location.
  7. Create an index.html file in the "demonstration-project" location.
  8. Run VSCode around the "demonstration-project" project folder.

## Submitting the assignment

- Submit a ".txt" file with a link to the recorded loom video through the form in the assignment page.

## NOTES

### Spaces in folder names

The proper naming convention for your projects should exclude spaces in the file and folder names. However, it is fine to use spaces for regular folders in your file system.

To create a folder with spaces in a multi-word name, you need to wrap it with double quotes when creating or referring to it in the terminal.

#### Example

```sh
mkdir "Some Folder"
cd "Some Folder"
```
