# Jenkins-Git Integration
This project demonstrates how to integrate GitHub with Jenkins to automate builds and deployments.

# Prerequisites

Jenkins installed and configured \
Git installed on the Jenkins server \
Credentials for the Git repository \
Git plugin installed on Jenkins 

# Steps

Install the Git plugin on Jenkins \
Create a new Jenkins job \
Configure the Git repository URL and credentials \
Set up a build trigger by enabling GitHub hook trigger for GITScm polling option \
under Postbuild actions  - Set GitHub commit status (universal) \
Save the Jenkins job \
Now setup github weebhook so that it triggers abuild whenever a user commits to this repository

# Conclusion 
By following these steps, you can integrate Git with Jenkins and automate your builds and deployments. 


![image](https://user-images.githubusercontent.com/126198458/235478683-c0a08608-abca-4d79-8077-2ce9e323aa5a.png)

![image](https://user-images.githubusercontent.com/126198458/235479353-ffd4f2d5-d6b0-4502-a045-e7bac7d2b927.png)





