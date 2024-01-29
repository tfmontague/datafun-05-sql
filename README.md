# datafun-05-sql
Repository for P5 project

## Project Workflow
1. Create a GitHub project repository with a default README.md.
 - [Quickstart for Repositories - GitHub Docs](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories)

2. Clone your repo down to your machine.
 -  Open a terminal in your Documents folder and clone the repo to your machine: 
 'git clone https://github.com/tfmontague/datafun-05-sql'

3. Open your project folder in VS Code (if you haven't already): 
'code .'

4. Add a .gitignore with .vsode/ and .venv/ and whatever else doesn't need to go in the repo:
 - Create a new file in the root folder of your project named .gitignore (using touch, ni, or your editor). Open .gitignore and add the following to ignore the .venv/ folder and .vscode (your editor settings).
'.venv/
.vscode/'

5. Create and activate a local virtual environment in .venv.
'python -m venv .venv'
'.venv\Scripts\activate'

6. Install your dependencies into your .venv and freeze your requirements.txt.
'python -m pip install logging'
 - verify if sqlite3 is installed in your Python in terminal using: 'python -c "import sqlite3; print(sqlite3.sqlite_version)'
 - if not, use  'pip install sqlite3' or 'pip install pysqlite3' to install

7. Record the commands used in your README.md.
 - [How to Write a Good README File for Your GitHub Project](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file)

8. Git add and commit with a useful message (e.g. "initial commit") and push to GitHub.
'git add .'
'git commit -m "initial commit".'

9. Create your first project files (usually in VS Code).

10. As you work, git add / commit / push to GitHub.
