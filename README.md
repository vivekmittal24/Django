# Django

Prerequisite: Sign Up for an AWS Account.
Create a User Directory with a User Pool.
Add an App to Enable the Hosted Web UI.
Add Social Sign-in to a User Pool (Optional)
Add Sign-in with a SAML Identity Provider to a User Pool (Optional)
Install an Amazon Cognito User Pools SDK.

==========================
IDE - VisualSource Code
Github
docker
Kubernetes
==========================
Functionality 
======================
Static Web Site 
Product Catalogue 
Store 
Login & Sign Up Module 

=======================
Infrastructure as a Code 
AWS EC2 
AWS S3
AWS Cognito
Magento
PaymentGateway

Standards
================
REST
JSON
DBMS
Python
Bootstrap/CSS



Frameworks
================
DJango/Flask
Anguar/REACT - 

Software
===========
PostgreSQL
Package Manager -  PIP / NPM 
Wordpress
Docker-Compose
NodeJS with NPM 
Python with PIP


Project Management 
===================
WBS
Effort Estimation
Resource 


System Design 
===================
Architecture
Prototype
UI


Stack 
=========
MEAN


Tools
==========
Docker
virtualenv
Cookiecutter template 
Taiga


Concepts
============
M(models.py)T(template.html)V(views.py)
Django data modles
Django Model - Inheritance
Convention over configuration


Commands 
Front-end environment
======================
npx create-react-app my-app 
yarn start
npm install --save bootstrap
npm install --save reactstrap
src/index.js --> import 'bootsrap/dist/css/bootstrap.css'

Back-end Environment 
=====================
pip install Cookiecutter
cookiecutter http://github.com/pydanny/cookiecutter-django

docker-compose -f local.yml build
docker-compose -f local.yml up

docker-compose -f local.yml run --rm django python manage.py createsuperuser 

Django App

===========

docker-compose -f local.yml run --rm django python manage.py startapp team 
add app to project config @ base.py config

Write class team/models.py


model_utils

register created models to the admin panel ( admin.py )

Refernces
========================
DjangoCentral
automationpanda.com
code.visualstudio.com
SpiceWorks

==========================
docker-compose -f local.yml run --rm python manage.py makemigrations
docker-compose -f local.yml run --rm python manage.py migrate

DJango Serializer

routing - urls.py 





VS CODE IDE Setup on UBUNTU
=======================================================================================
https://www.youtube.com/watch?v=rWyWt3DR9Fs DP
https://community.spiceworks.com/how_to/155718-install-xrdp-on-ubuntu-18-04 - RDP
https://linuxize.com/post/how-to-install-visual-studio-code-on-ubuntu-18-04/ - VSCODE
sudo apt-get install ubuntu-desktop
startx
sudo code --user-data-dir=~/root

Ubuntu

sudo adduser lubos

sudo usermod -aG sudo lubos

su lubos

apt update

sudo apt upgrade

sudo apt dist-upgrade

sudo add-apt-repository universe

sudo add-apt-repository multiverse

sudo apt install tasksel

sudo tasksel

sudo reboot

sudo apt-get install ubuntu-desktop

sudo apt-get install xubuntu-desktop

sudo apt-get install kubuntu-desktop

sudo reboot

apt install xserver-xorg-core

sudo apt install xrdp xorgxrdp -y

echo mate-session> ~/.xsession

sudo apt-get install mate-core

sudo ufw allow 3389/tcp

sudo reboot

Install VScode IDE
sudo apt install software-properties-common apt-transport-https wget
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
sudo apt update
sudo apt install code



=========================================================================================

GIT/GITHUB Setup on Ubuntu with VSCode
=======================================
Reference : https://www.youtube.com/watch?v=Fk12ELJ9Bww
https://www.youtube.com/watch?v=ZMgLZUYd8Cw
https://www.youtube.com/watch?v=9cMWR-EGFuY

Add VSCode project to git and github
Add commit and push whenever changes happen
Clone from github to vscode
Remove project from git

Installing GIT on ubuntu
Create a Repository in Github

sudo apt-get install git -y
git --version
git config --global user.name "user1"
git config --global user.email "abc@gmail.com"
git config --list
gedit .gitconfig
git clone <respository url>
cd 
git status
git add <filename>
git commit -m "description" <filename>
git push -u origin master

Ubuntu Commands
find / -name <file-name>
