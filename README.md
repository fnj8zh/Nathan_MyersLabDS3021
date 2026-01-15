# This repo creates a new working project environment using the following recipe (also in https://github.com/fnj8zh/daytwostuff/blob/main/new_file.py)
# Recipe: 
# 1. Create a new GitHub repository for your project, or fork an existing repository to your GitHub account. 
#    Then create a Codespace from the new repository or fork, and connect it to your local VS Code.
# 2. Create a virtual environment in the Codespace to manage dependencies and ensure the correct extensions are installed.
#    Run:
# python3 -m venv venv
# source venv/bin/activate
# 3. Install necessary packages using pip, and save them to a requirements.txt file:
# pip install <packages>
# pip freeze > requirements.txt if necessary
# 4. Add a .gitignore file to exclude unnecessary files, like:
# venv/
# __pycache__/
# *.pyc
# .vscode/
# 5. Add a README.md file describing your project
# 6. Stage and commit your initial setup to Git:
# git add .
# git commit -m "Initial commit: setup project environment, requirements, .gitignore, README"
# 7. Push your changes to GitHub:
# git push origin main