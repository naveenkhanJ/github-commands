🚀 Git Basics for IT Undergraduates

This guide covers the most essential Git commands every beginner should know.
Perfect for university projects and team collaborations.

📌 What is Git?

Git is a version control system that helps you:
Track changes in your code
Collaborate with teammates
Maintain project history
Avoid losing work

🛠️ 1. Initial Setup (Run Once)

Set your username and email (should match your GitHub account):

git config --global user.name "Your Name"
git config --global user.email "your@email.com"


Check configuration:

git config --list

📂 2. Create or Start a Project
🔹 Initialize a New Repository
git init


This creates a .git folder to track your project.

🔹 Clone an Existing Repository
git clone https://github.com/username/repository-name.git


This downloads a project from GitHub to your local machine.

📊 3. Check Project Status
git status


Shows:

Modified files
Staged files
Untracked files

👉 This is the most frequently used Git command.

➕ 4. Add Files to Staging Area

Add specific file:

git add filename


Add all files:

git add .

💾 5. Commit Changes
git commit -m "Short meaningful message"


Example:

git commit -m "Added login page UI"


✔ Always write clear commit messages.

🔄 6. Connect to GitHub (First Time Only)
git remote add origin https://github.com/username/repository-name.git

☁️ 7. Push Code to GitHub
git push origin main


If using another branch:

git push origin branch-name

⬇️ 8. Pull Latest Changes
git pull origin main


Always pull before starting work in a team project.

🌿 9. Branching (Very Important)

Create a branch:

git branch branch-name


Switch to branch:

git checkout branch-name


Create & switch in one command:

git checkout -b branch-name

🔀 10. Merge Branch

Switch to main branch:

git checkout main


Merge:

git merge branch-name

❌ 11. Fixing Mistakes

Unstage file:

git restore --staged filename


Discard changes:

git restore filename

📜 12. View Commit History
git log


Compact version:

git log --oneline

📌 Basic Workflow Summary
git add .
git commit -m "Your message"
git push origin main

Common Commit Types:

feat: A new feature.

fix: A bug fix.

docs: Documentation changes.

style: Formatting, missing semicolons, etc.

refactor: Code changes that neither fix a bug nor add a feature.

test: Adding or correcting tests.

chore: Updating build tasks, package manager configs
