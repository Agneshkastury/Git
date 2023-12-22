# Git

##Install and set up Git on Ubuntu:

  1. Update Package Lists:
     ```
     sudo apt update
     ```

  2. Install Git:
     ```
     sudo apt install git
     ```

  3. Verify Installation and check version:
     ```
     git version
     ```
     
  4. Configure Git to Set your name and email address (used for committing changes) by running the following commands:
     ```
     git config --global user.name "Your Name"                #git_account_username_casesensitive
     git config --global user.email "your.email@example.com"  
     ```

  5. Checking Configuration
     ```
     git config --list
     ```

  6. Optional - Set Default Text Editor
     ```
     git config --global core.editor "editor-name"
     ```
Replace "editor-name" with your preferred text editor, such as "nano," "vim," or "code" (for Visual Studio Code).

Now you have Git installed and configured on your Ubuntu system. You can start using Git for version control in your projects. Here are a few additional commands to help you get started:

Basic Git Commands:
Initialize a Repository:

bash
Copy code
git init
Clone a Repository:

bash
Copy code
git clone <repository_url>
Check Status:

bash
Copy code
git status
Stage Changes:

bash
Copy code
git add <file(s)>
Commit Changes:

bash
Copy code
git commit -m "Your commit message"
Push Changes to a Remote Repository:

bash
Copy code
git push origin <branch_name>
Pull Changes from a Remote Repository:

bash
Copy code
git pull origin <branch_name>
These are just some of the basic Git commands.
