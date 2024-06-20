# PLPBasicGitAssignment
 Creating a Hands-On Assignment: Basic Git And GitHub Workflow

## The steps I took to create my repository and text file

###  Repository Setup

**Step 1: GitHub Repository Creation**
1. I logged in to my GitHub account.
2. Then, I created a new repository on GitHub and named it "PLPBasicGitAssignment".
3. While setting it up, I made sure to initialize it with a README file to get started smoothly.

###  Local Setup

**Step 2: Local Folder Setup**
1. On my local machine, I created a new folder and named it "PLPBasicGitAssignment" as instructed.
2. I opened my VS code terminal and navigated to the folder I had created.

**Step 3: Git Initialization**
1. In the VS code terminal, I initialized a new Git repository within the "PLPBasicGitAssignment" folder by running the command:
   
   git init
   

**Step 4: Connecting to GitHub**
1. Next, I linked my local repository to the GitHub repository I created earlier. I used the following command, replacing `<repository-url>` with the actual URL of my GitHub repository:
   
   git remote add origin <repository-url>
   

###  Making Changes

**Step 5: Create a File**
1. Inside my local "PLPBasicGitAssignment" folder, I created a new text file named `hello.txt`.

2. I opened `hello.txt` and added a simple text message: "Hello, Git!" and a little extra message.

**Step 6: Committing Changes**
1. I staged the changes by running the command:
   
   git add hello.txt
   
2. Then, I committed the changes with a meaningful message:
   
   git commit -m "Add hello.txt with a greeting"
   

###  Pushing to GitHub

**Step 7: Pushing to GitHub**
1. Finally, I pushed the committed changes to my GitHub repository using the command below:  

   git push -u origin main
   

###  Verification

**Step 8: Verify on GitHub**
1. To make sure everything worked correctly, I visited my GitHub repository in a web browser.
2. I confirmed that the `hello.txt` file and my commit message were visible.

