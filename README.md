#Install Git in Ubunto
sudo apt-get update
sudo apt-get install git
git config --global user.name "Your name"
git config --global user.email "Your email"

####reference
https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-14-04

#Install Git in Windows

####reference
https://git-scm.com/
https://git-for-windows.github.io/
http://code.google.com/p/tortoisegit/

#Basic Instruction
git init
git status
git add "filename"
git add .
git commit -m "comment"
git log

git remote add origin URL
git remote -v 
git push -u origin master
git pull origin master

