# Fab-Academy-2017

Nick Langhoff and Marco Wehrfritz
working on Fab Academy assignment 2017

URL: https://github.com/SkyFabLab/Fab-Academy-2017.git

Create repsitory via command line:

echo "# Fab-Academy-2017" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/SkyFabLab/Fab-Academy-2017.git
git push -u origin master

push an exisiting repository:

git remote add origin https://github.com/SkyFabLab/Fab-Academy-2017.git
git push -u origin master


git clone https://github.com/SkyFabLab/Fab-Academy-2017.git
- download the folder from github.com

cd Fab-Academy-2017.git
- open the downloaded directory

git status
- check for new files and synchronisation

- open the Fab-Academy-2017.git as a project
folder in an editor you like (I used ATOM)
- write a file (I used "Marco.html") and save it in this folder

git add Marco.html
- add my file to the repository
- add -A adds all changed files

git status
- showes new file to submit

git commit -m "..."
- -m means message and between "" you can write someting"

git push
- uploads all your changes

git pull
- from the .git directory downloads all new files including the pushed
changes of the others in the local folder
- to beginn with, go in the .git folder and get up to datye before start working

If you forgot to add -m to commit,
