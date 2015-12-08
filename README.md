# Test1
# KickProject
Target of the project is to create an public webpage build by client side routes and make it work under SEO rules.

# Installation
Windows: To install all tools which are needed to run website on local maching, you have to download soft from below webpages: <br />
1) git: https://git-scm.com <br />
2) nodejs: https://nodejs.org <br />
3) mongodb: https://www.mongodb.org/downloads <br />
Linux: Simply run those commands
apt-get install git nodejs-legacy npm mongodb

# Git
To use github you have to install ssh keys on your pc. Here are an tutorial for that: https://help.github.com/articles/generating-ssh-keys/ <br />
Paste your ssh public key to the github settings, you are ready to use git.<br />
Open your local terminal and move to the folder you want to host the project. <br />
git init <br />
git remote add origin git@github.com:CrackerakiUA/myBeautifulUkraine.git <br />
git pull origin master <br />
npm install <br />

# MongoDB (windows)
On the location of mongodb installation you have to create a folder for data. Then drop in that folder cmd.exe and start.bat file. In start.bat file write this line "D:\Work\DevMongoDB\bin\mongod --dbpath D:\Work\DevMongoDB\data --journal", and modify the path to your mongodb folder in this script. To run mongodb you have to open this cmd and simple write start.bat. Suggestion, create an shortcut on desktop so you can run it easly. <br />
P.S. on linux you simply do nothing of this.

# Run
Make sure you have mongodb open and running. To put the webiste online on local, you have to open terminal and simply write: node server.js

# Updates
From time to time there could be needed to run again npm install, if developers add new modules.

# Feedback
If you have any question on setup feel free to ask.
