# Devops-Project2
This project is about implementing a CI/CD pipeline using the following tools                       
(1)Git : For version control (2)Jenkins : For continous integration and Continous deployment (3)Docker : For deploying containerized applications (4)Puppet : For configuration management (5)Selenium : For automating test on the deployed web application


As soon as the Developer pushes the updated code on GIT master branch, a new test server is provisioned with all the required software.Post this, the code is containerized and deployed on the test server.The deployment is then tested using Selenium, and if the build is successful,it should be pushed to production server.
