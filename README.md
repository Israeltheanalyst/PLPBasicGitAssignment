## GIT
### Created a new repository on GitHub (let's call it "PLPBasicGitAssignment").

### Created a new folder on your local machine (e.g., "PLPBasicGitAssignment").
### - Opened a terminal or command prompt and navigate to the created folder.(GIT BASH)
### Initialized a new Git repository in your local folder.

### I Linked my local repository to the GitHub repository you created.git remote add origin <repository-url>

### Created a File: - Inside my local folder, I created a new text file (`hello.txt`). -  Added a simple text message ("Hello, Git!").

###  Committed my Changes: git add hello.txt git commit -m "Add hello.txt with a greeting"

### Pushing to GitHub:- Push the committed changes to my GitHub repository.
### git push --force origin main (I used force because there is no conflict.. I was not working with any team.. There is a better approach to this tho ) ⬇⬇⬇⬇
git pull origin main
git pull --rebase origin main
