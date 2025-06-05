# Git-init-tips

Step-1:
Make sure you have:
-> Installed Git
-> A GitHub account
-> VS Code installed.
Step -2:
 Create a GitHub Repository
1) Go to https://github.com
2) Click "New" to create a new repository
3) Give it a name (e.g., my-first-project)
4) Optional: Add description, keep it public or private
5) Do NOT check "Initialize with README".
6) Click "Create repository"

Step-3:
1)Open Your Project in VS Code
=> Open your local folder in VS Code (File > Open Folder).

2) Open Terminal in VS Code
=> Go to Terminal > New Terminal.

3)Initialize Git in Your Project
In the terminal, type:
-git init
This sets up Git in your folder.

4) Add Your Files to Git
git add .
This stages all your files for commit.

5)Commit the Files.
git commit -m "First commit"
This saves your staged files with a message.

6) Link Local Git to GitHub
Copy the URL of your GitHub repo (looks like https://github.com/username/repo-name.git)
Then run:
git remote add origin https://github.com/your-username/your-repo-name.git.

7) Push Your Code to GitHub
git push -u origin master
If you get an error like master -> main, use:
git push -u origin main

✅ You're Done!
Now refresh your GitHub repo page — your code should be there!
To update your repo in the future:
git add .
git commit -m "your message"
git push

You can also install the GitHub extension in VS Code for an easier UI.


