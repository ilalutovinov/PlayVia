# PlayVia 

## Git Installation:

1. First, make sure you have Git installed. If not, you can download it [here](https://git-scm.com/downloads).

2. Run the installer and follow the installation instructions, leaving all settings at their defaults.

## Git Configuration:

1. After installation, open Git Bash. To do this, type "Git Bash" in the search and launch the Git command line.

2. Enter the following commands to set your username and email address:
```bash
git config --global user.name "Yourname on GitHub"
git config --global user.email youremail.gmail.com
```
2. To verify that the settings have been successfully set, execute the command:
```bash
git config --list --show-origin
```
### Connecting to Repository in Visual Studio Code:

1. Make sure you have an account on GitHub. If not, sign up for GitHub [here](https://www.python.org/).

2. Open Visual Studio Code (install it if you don't have it). If not, you can download it [here](https://code.visualstudio.com/).

3. Install the Git extension for Visual Studio Code if it's not already installed.

4. Open the terminal in Visual Studio Code (press Ctrl + ~) to enter Git commands.

5. Enter the following command to clone the repository to your computer:
```bash
git clone https://github.com/ilalutovinov/PlayVia.git
```
### Starting the server:

1. Open command line and paste the code:
```bash
python manage.py runserver
```
2. If an error occurs, make sure you have Python installed. If not, you can download it [here](https://www.python.org/)

3. After installation, enter the commands in the Visual Studio Code terminal:

Version check:
```bash
python -V
```
Installing Django:
```bash
pip install django 
```

2. After successful launch of the search engine, insert:
```bash
http://127.0.0.1:8000/
```

### Instructions for use: 

1. Every time you visit the project, do not forget to run the following command to update your local content:

```bash
git pull
```
2. Don't forget to write the version.

3. When updating repository content in Git and in the project itself, please remember to sign and describe each change. This helps us better understand what changes are being made and why they are important. A detailed description of the changes will make it easier to maintain the project and make collaboration more productive.

Please pay special attention to describing each commit in Git so that other team members can quickly understand the changes made. Make the same changes to the project itself, if necessary.

Thank you for your attention to this issue!

