#CICD #1

- In this project we will create a simple CICD pipeline
- The Tech Stack Used is Jenkins Terraform AWS ec2.
- We will Deploy a simple Flask APP on a ec2 instance using Jenkins .



Steps:-
1. create and Aws account if you dont have one .
2. create a IAM user with all administrative access (you can restrict it to have only ec2 rights or required services to manage the RBAC more effectively)
   I'll be using it to login into my AWS account , therefore I am providing it all Administrative access.
4. Create an ec2 instance (additionally you will also create a key pair and security group in the process)
5. once you ec2 instance is create , update all existing packages.
6.Install jenkins and its dependencies . (you can find the jenkins installition details here https://www.jenkins.io/doc/book/installing/)
   Also make sure to open port 8080  in security group . 
7. once jenkins is installed , run the jenkins.service
8. use public ip and port 8080 to access jenkins on your host machine 
9. (optional try running a test job)


