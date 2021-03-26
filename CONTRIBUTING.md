# This is a documentation on how to Contribute 


The documentation can be found at [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).

How to get started 

1. Fork this project. ( It's found at the top right corner of the repository )
   - This will make a working copy of the project in your github repository 
2. Clone the repository. ( Go to your profile and find the link as https://github.com/<yourusername>/frontend-project ) 
   - Make sure that Git is installed in your system 
   - Go to command line or terminal depending on your Operating System 
   - Enter command `git --version` to verify if Git is install properly. You will see result like this `git version 2.28.0.windows.1`
   - After successfully installing git, Go to the directory where you want the projec to be. Could be Destop or Documents 
   - User the following command to clone the repository
     - `git clone https://github.com/<yourusername>/frontend-project`
   - You will see the project will be downloaded in your local system. You shouldn't use the Github WebPage to do any kinds of edits or commits
3. Since new commits will be made every time, make sure to update the local respoitory with remote repository.
   - Use the command `git pull origin main`
   - As you can see our production ready branch is main. You can have other branches like master or anything working on other projects 
4. Whenever you want to work on some issue, make sure to create a new branch
   - Use the command `git branch` to list all the branches in the repository
   - If you are working on documentation, to create a new branch `git checkout -b documentation\newfeature`
   - You will be switched to new branch 
   - Its possible that while you are working on branch, there could be some update on the main branch 
   - Use the command `git pull origin main` again
5. Make some changes in the any IDE or Code Editor you like . Eg. VSCODE or Sublime 
6. Save the changes 
7. If you are done working. Use the follwing command see the status 
   - `git status`
   - If you see some line with red, that means that the files has been changed
8. Add the modified files in the current directory to staging area with the follwoing command 
   - `git add .`
9. You are ready to commit your changes 
   - `git commit -m "Changes you made" `. - m is the message you want to add. It could be able the changes that you made
10. Push the changes 
   - `git push origin <your branch name>`
   - Eg. `git push origin documentation\test`
11. Thats it. 
## Thank you for contributing. Hope you were able to learn something from this project. 
