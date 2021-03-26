# This is a documentation on how to Contribute 


## Contributing
Thank you for considering and taking the time to contribute! This is project is all about to teach students how can they start working on open source projects.

The following are guidelines for contributing to this project.

### :triangular_flag_on_post: Forking repository :
1. Firstly you have to make your own copy of project. For that you have to fork the repository. You can find the fork button on the top-right   side of the browser window. 
2. Kindly wait till it gets forked.
3. After that copy will look like ```<your-user-name>/frontend-project``` forked from ```it-bud/frontend-project```.

### :triangular_flag_on_post: Clone repository:
1. Go to command line or terminal depending on your Operating System.
2. Type the following command
    *  ```git clone https://github.com/<yourusername>/frontend-project```
3. You will see that project will be downloaded in your local system.  

### :triangular_flag_on_post: Creating a branch: 
Whenever you want to contribute to any project. It is best practice that you should create a branch and push the branch as PR rather than directly pushing main/master branch
1. ```git branch``` will list all the branches in the repository
2. Now type ```git branch <your-branch-name>``` to create your branch
3. You can check the created branch by ```git branch```
4. But still if you start editing the edits will go to the main branch. To change the path , type in ```git checkout <your-branch-name>```
5. Now you are ready to do the desired changes.

### :triangular_flag_on_post: Pushing your changes:
After doing the changes, and when tests are successfully passing you can push your changes to remote.
1. Goto your terminal and type ```git status``` and hit enter, this will show your changes from the files
2. Then type in ```git add``` and hit enter, this will add all the files to staging area
3. Commit the changes by ```git commit -m "<message-describing-your-change>"``` and hit enter.
4. Now push your branch to your fork by ```git push origin <your-branch-name>``` and hit enter.

### :triangular_flag_on_post: Creating a pull reques:
1. After successfully pushing your code to your local repository on github, now to merge your code into the main code you need to create a pull request.
2. Click on ```Compare and pull request``` button.
3. You will see a template.
4. Fill the template completely by describing your change, cause of change, issue getting fixed etc.
5. After filling the template completely click on ```Pull request```
6. That's it.