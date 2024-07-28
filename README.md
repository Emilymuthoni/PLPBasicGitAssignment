1. GitHub Repository Creation:
Log in to your GitHub account.
Create a new repository:
Click on the "New" button or the "+" icon in the top-right corner and select "New repository".
Name the repository PLPBasicGitAssignment.
Check the box that says "Initialize this repository with a README".
Click "Create repository".

2. Local Folder Setup:
Create a new folder on your local machine, for example, PLPBasicGitAssignment.

Open a terminal (Command Prompt, PowerShell, or Terminal depending on your OS).

Navigate to the folder you created:

cd path/to/PLPBasicGitAssignment
3. Git Initialization:
Initialize a new Git repository in your local folder:

git init
4. Connecting to GitHub:
Link your local repository to the GitHub repository you created:

git remote add origin https://github.com/your-username/PLPBasicGitAssignment.git
Replace your-username with your actual GitHub username.

Task 3: Making Changes
5. Create a File:
Inside your local folder, create a new text file named hello.txt.
Add a simple text message to the file, e.g., "Hello, Git!".
You can create and edit the file using any text editor, or you can use the terminal:

echo "Hello, Git!" > hello.txt
6. Committing Changes:
Stage the changes:


git add hello.txt
Commit the changes:


git commit -m "Add hello.txt with a greeting"
7. Pushing to GitHub:
Push the committed changes to your GitHub repository:


git push -u origin main

8. Verify on GitHub:
Visit your GitHub repository in a web browser.
Confirm that the hello.txt file and the commit message are visible.