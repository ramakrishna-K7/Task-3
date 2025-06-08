                          TASK 4: Build a Version-Controlled DevOps Project with Git

1. Initializing a Repo:
    
•	Open terminal
•	Create a directory
mkdir task3 && cd task3
git init
________________________________________
Creating & Pushing to GitHub :

•	Create repo on GitHub 
•	Copy remote URL and run:
git remote add origin https://github.com/ramakrishna-k7/task3.git
git branch -M main
git push -u origin main
________________________________________
3. Creating Branches (dev, feature):
   
git checkout -b dev
git push -u origin dev
git checkout -b feature
git push -u origin feature
________________________________________
4. Let’s add a proper README and .gitignore:
   
Readme:
       DevOps Task 3
.gitignore:
         *.log\n.env\nnode_modules
________________________________________

•	Open pull request from feature → dev
•	Merge
“Next, I open a pull request from my feature branch to dev and merge it — a key part of Git workflow.”
I updated my local repo (dev branch) with  the cmd of 

  Git pull 
________________________________________
6. Adding tags:

git checkout main
git merge dev
git tag v1.0 -m "Initial release"
git push origin –tags





