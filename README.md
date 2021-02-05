# Project phone-books : Full integration chain test


## Description

* This is a complete pipeline CI/CD with Jenkins to deploy a python application in production
* This infrastructure it's componed of 4 servers (githubserver, SonarServer, build server and production server)
* We use cloudformation, Jenkins, Ansible, Docker, Git and GitHub tools
* The differents stages are :
1. Ensure lint syntax of diferents langages (bash, yamel and markdown) is OK
2. Ensure servers are availables
3. Ensure syntax ansible is OK with ansible-lint
4. Build image on the build server and push artifact on the artifactory docker
5. Deploy application on the production server
6. Ensure application is deployed

by Lusianne DJEPANG (lusiannedjepang@gmail.com)

