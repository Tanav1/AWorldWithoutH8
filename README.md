# [AWorldWithoutH8](https://tanav1.github.io/AWorldWithoutH8/)
## **Getting Started**
### Tech Stack:
Front-End - [Django REST framework](https://www.django-rest-framework.org/)
<br> Text Editor - [Sublime Text Editor](https://www.sublimetext.com/)


### Resources:
<br> Official Documentations - [Django](https://docs.djangoproject.com/en/3.0/), [Django REST](https://www.django-rest-framework.org/)
<br> Useful Medium articles for setup - [Medium](https://medium.com/@diwassharma/starting-a-python-django-project-on-mac-os-x-c089165cf010)


## Please follow these guidelines to develop further on this project:

### 1. Setting up the environment:
1. Make a folder named `AWorldWithoutH8` and inside it clone this repo using `git clone <projecturl>` 
2. Download and configure Django 


### 2. Coding rules for the Dev Team:
1. There should be no dead code or unnecessary comments in any of your commits
2. Your function and request names should briefly explain what it is about 
3. Always add the name of the packages you download in `AWorldWithoutH8/requirements.txt`
4. Before you compile anything, go to your `AWorldWithoutH8` directory and execute `pip install -U -r requirements.txt` to download all backend dependencies
5. Inside the `AWorldWithoutH8/frontend` folder, also execute `npm install` to download all your frontend dependencies mentioned in `package.json`


### 3. Rebasing with master

1. Whenever there are new changes in master, you maybe required to integrate those changes on your branch before working on top of it
2. Update your cache with `git fetch origin`
3. Run `git rebase origin/master` to execute the rebase
4. There will be merge conflicts and you'll have to manually solve them. Once done, use `git add` to add all files with resolved conflicts (you can get a list of these with `git status`), and then run `git rebase --continue`. DO NOT run `git commit` or make a commit while resolving merge conflicts.
5. Finally, once sure of the new changes, execute `git push --force` to update your branch with these new changes. NEVER run `git push --force` on the master branch



#### *Don't get stuck for too long. Ask your team members for help. Effective communication will lead this project to be a success and worth writing about in your resume. And above all, don't forget to have some fun!*
