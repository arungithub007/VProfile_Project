# VProfile_Project

## About the Project
* Multitier  web application stack
* setup on laptop/desktop
* This project acts as baseline for upcoming projects
* Helps us to setup any project locally
  
## Scenario
* working in a project
* variety of services that powers ur project runtime
* runbook / setup doc for setup stack

## Problem
* not comfortable in making changes in servers
* local setup is comlex
* time consuming
* not repeatable
  
## Solution 
* get a local stup >> automated >> code IAAC >> Automated
  
## Tools
* Hypervisor ---> ORACAL VM VIRTUALBOX
* AUTOMATION ---> VAGRANT
* CLI        ---> GIT BASH
* IDE        ---> Sublime_text/vscode/notepad++
  
## OBJECTIVE
* VM automation locally
* BAseline for upcomming projects
* Realworld project setup locally {for R & D}

## ARCHITECTURE OF PROJECT SERVICES
* NGINX --->  is a web service to create loadbalancing experrience.
* TOMCAT ---> it is **java web appication service**
* RABBIMQ ---> it is a queing agent (message brocker)
* MEMCACHED ---> it is a Database caching connected to mysql server
* MYSQL ---> is database

## ARCHITECURE OF AUTOMATED SETUP
* vagrant
* virtualbox
* gitbash
* some scripts and commands
  
## FLOW OF ENTIRE STACK
* setup tools metioned in prereqs
* clone source code
* cd into vagrant dir
* bringup Vms
* validate
* setup all the servies
  * mysql
  * memcahed
  * rabbit MQ
  * tomcat
  * nginx
  * App Build and diploy
* Verify from browser
  
  
   
  ![alt text](<Re-Architecture WebApp on AWS Cloud.png>) ![alt text](<vprofile projectsetup Automate.png>) ![alt text](<Vprofile projectsetup Manual.png>) ![alt text](<Ansible for complete stack first execution.png>) ![alt text](<Ansible for complete stack second execution.png>) ![alt text](<Ansible for complete stack third execution.png>) ![alt text](<Architecture Of Continous Delivery PipeLine.png>) ![alt text](<AWS CI_CD Project.png>) ![alt text](<CICD for Docker Kubernetes Using Jenkins.png>) ![alt text](<Containerization of Java Project using Docker.png>) ![alt text](<Continous Delivery And Configuration Management(jenkins plus Ansible).png>) ![alt text](<Continous Delivery of Java Web Application.png>) ![alt text](<Continous delivery on AWS Cloud(Java App).png>) ![alt text](<Continous Integration On AWS Cloud.png>) ![alt text](<Continuous Integration Using Jenkins,Nexus,Sonarqube& Slack.png>) ![alt text](<EMart App Architecture.png>) ![alt text](<Java App Deployment on Kubernetes Cluster.png>) ![alt text](<Terraform for cloud State Management Converted.png>) ![alt text](<VPC Design & Components.png>) ![alt text](<VPC Diagram.png>) ![alt text](<Ansible Architecture.png>) ![alt text](<Ansible for AWS VPC.png>) ![alt text](<AWS Lift&Shift project.png>) ![alt text](<CICD for Containers.png>) ![alt text](<High Avalability VPC.png>)
