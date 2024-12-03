# Module 1
Git and GitHub

GitHub is a distributed version control system that is designed to track changes over multiple users and versions,
and allows a team to merge individual efforts and edits to current code.

You always push up to GitHub and pull down from GitHub to your local device

## Notable commmands:
### Basic Configuration (Used once on a device to set up connection)
git config --global user.name "Your username"
git config --global user.email "yourmail@example.com"

### Creating a repo:
git init
git remote add origin https://github.com/YourUsername/repository-name.git
git branch -m main
git add .         (use "." for all files, or filename)

*note- "origin" is essentially a variable that holds the value of the URL for your repository
*remote add origin "URL" assigns the variable

### Create a new branch:
git branch new-feature

### Switch to the new branch:
git checkout new-feature

### Make changes and commit them to the new branch:
Make any required changes and then use the following commands:
git add . 
git commit -m "Add new feature" 

### Merge changes back into the main branch:
git checkout main
git merge new-feature

### Pushing to GitHub:

Link local Git repository to the remote GitHub repository:

git remote add origin <link-of-github-repo>
Stage and commit changes locally:
git add .
git commit -m "Added a new feature"

Push changes to GitHub:
git push origin main
