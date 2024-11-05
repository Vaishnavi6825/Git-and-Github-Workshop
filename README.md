# Git-and-Github-Workshop-DRESTEIN-24<br>
NAME            :  KIRUTHIKA M<br>
REGISTER NUMBER :  212222060121<br>
DEPARTMENT      :  ECE<br>
YEAR            :  3RD YEAR<br>


Git and GitHub Workshop Assignment  <br>
Complete the following tasks to practice core Git commands. Answer each question and perform the associated Git operations.  <br>
 
1. Setup and Initialize:<br>
    
- 	What command do you use to create a new directory named `git-workshop` and navigate into it?  <br>
ANSWER: mkdir git-workshop <br>
        cd git-workshop <br>
 
2. Initialize a Git Repository:<br>
   
	- 	What command initializes a Git repository in your directory?  <br>
ANSWER: git init <br>
 
4. Create and Modify Files:<br>

- 	How do you create a new ile named `hello.txt` and add the content 'Hello, Git Workshop!' to it using a single command?  <br>
ANSWER: echo "Hello, Git Workshop" > hello.txt <br>
 
4. Check the Status of Your Repository:<br>
   
	- 	What command displays the status of your repository?  <br>
ANSWER: git status <br>
 
6. Stage and Commit Changes:<br>
   
	- 	What command stages the ile `hello.txt`?   <br>
ANSWER: git add hello.txt <br>
 
- What command commits the staged ile with the message 'Add hello.txt with welcome message'?  <br>
ANSWER: git commit -m "Add hello.txt with welcome message" <br>
 
6. Branching:<br>
   
	- 	What command creates a new branch named `update-content`?  <br>
ANSWER: git branch update-content <br>
 
-How do you switch to the `update-content` branch?  <br>
ANSWER: git checkout update-content <br>
 
7. Make Changes on the Branch:<br>
   
- 	What command would you use to append the text 'This is a simple Git assignment.' to `hello.txt`?  <br>
ANSWER: echo "This is a simple Git assignment" >> hello.txt <br>
 
- 	What command stages and commits the changes with the message 'Update hello.txt with additional message'?  <br>
ANSWER: git add hello.txt git commit -m "Update hello.txt with addi onal message" <br>
 
8. Merge Changes:<br>
   
-	What command switches you back to the `main` branch?  <br>
ANSWER: git checkout main <br>
-	How do you merge the `update-content` branch into `main`?  <br>
ANSWER: git merge update-content <br>
 
9. View Commit History:  <br>
	- 	What command shows the commit history? <br> 
ANSWER: git log <br>
 
10. Undo and Reset (Practice Safely):
    
- 	If you make a change to `hello.txt` that you want to revert before committing, what command would you use?  <br>
ANSWER: git checkout -- hello.txt <br>
- 	How can you reset your branch to a previous commit (optional, for advanced practice)?  <br>
ANSWER: git reset --hard <commit-hash> <br>
 
11.Push to a Remote Repository (Optional):  <br>
 
  -What command adds a remote repository named origin ?<br>
ANSWER: git remote add origin <repository-url> <br>
 
12.What command pushes your local `main` branch to the remote repository? <br>
 
ANSWER: git push origin main <br>
 



