# Reverse-Eng-Code

Links
Github Link - https://github.com/ryan-gon/Reverse-Eng-Code/blob/master/README.md

GoogleDoc Link - https://docs.google.com/document/d/1hCt7Wtp5Syebvq4B6FsWjhUOvhyOIVSVRDRY8JADx8c/edit?usp=sharing


Sequelize Reverse Engineering Code

Overview and Purpose

When joining a new team, you will be expected to inspect a lot of code that you have never seen before. Rather than having a team member explain every line for you, you will dissect the code by yourself, saving any questions for a member of your team.
This tutorial is a walkthrough for developers to assist in understanding the code.
This code uses npm modules ‘express’, ‘passport’, ‘fs’, ‘path’ to help users create an account, login into that account and logout storing all data in a mysql database.


User Story
As a developer I want a walk-through of the codebase so that I can use it as a starting point for a new project.


Step by Steps Code Guide

1. Clone repo from github into VSS using gitbash terminal git clone "REPO"

2. Open Mysql workbench and create and use 3 databases (‘passport_demo’, ‘database_test’, ‘database_production’) then press the lightning bolt to run the scripts in the database.

3. Edit the config.json in the config folder → edit ‘development.password’, ‘test.password’, ‘production.password’ and input your personal mysql password.

4. Go to Sequelize-Reverse-Engineering-Code-HW/develop → right click and open terminal → then run NPM install to install required modules

5. When installs complete, run node server.js to activate the app

6. Go to the browser and type in http://localhost:8080/ as web address. Enjoy!


Technologies Used

 npm install 
 passport
 express 
 MySql - sequelize
 fs
 path
 CSS 
 HTML 
 .js
 
 
