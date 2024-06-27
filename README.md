# Deploying Flask Application to Azure Web App using GitHub Actions

# Tasks Performed
## 1. Directory and Environment Setup
     Created our project directory named Flask-AzureWebApp.
     Activated a virtual environment for Python using venv.
    these screenshots dhows the used command - 
![Screenshot](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot202024-06-2720145637.png)

![Screenshot](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27150642.png)

## 2. Flask Application Development
  I Developed a Flask application (app.py) with a basic endpoint returning "Hello, Azure Web App!".
  The screenshot shows the written code for application-
![Screenshot](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27145754.png)


## 3. Dependency Management
    I have Configured requirements.txt with necessary dependencies, including Flask by.
![Screenshot](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27150432.png)
![Screenshot](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27150817.png)


## 4. Initialized the Git repository, added files (app.py, requirements.txt) and made our first commit 
    I initialized our git repository and added files into it and made our first commit. then I created a repository at Github and added its remote url.
    Note : the github repository is shown in next step.
![Screenshot_displaing_repo_initialization](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot 2024-06-27 150833.png)
![Screenshot_displaying_commit](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27150933.png)
![Screenshot_displaying_remote](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27151102.png)

## 4. GitHub Repository Setup
    Created a GitHub repository named Flask-AzureWebApp-Assignment.In this repository we have pushed our application files.

![Screenshot_displaying_pushing_content](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27151142.png)
![Screenshot_displaying_repo_content](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27151206.png)


## 6. Azure Web App Creation
   Created an Azure Web App named flask-azurewebapp-assignment.
   Configured the Azure Web App with Python 3.12 environment.
   I have created this WebApp in Central India region.
   I have selected Linux envrionment in which we will be deploying our application in next steps.
   ![Screenshot_displaying_Webapp](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27151410.png)
   ![Screenshot_displaying_webapp](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27151424.png)

   thus we have created our webapp and the provisioned resource is shown in the image
   ![Screenshot_displaying_created_webapp](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27151530.png)



## 7. Deployment Configuration
    Utilized WebApp's Deployment Center to link the GitHub repository (Flask-AzureWebApp-Assignment) for automated deployment.
    Configured deployment settings to deploy from master branch.
![Screenshot_displaying_created_webapp](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27151607.png)



## 8. Deployment Process
    After clicking on save button shown in above image, our deployment started from Github Actions to Azure WebApp using CI/CD methos.
    These screenshots shown the deployment procedure-
![Screenshot_displaying_github_action](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27152317.png)
![Screenshot_displaying_deploy_action](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27152402.png)
![Screenshot_displaying_deploysuccess](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27170138.png)

![Screenshot_displaying_deploysuccesscenter](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27152753.png)



## 9. Verification and Access
    
    After successfull deployment of our flask application into Azure WebApp , I have visited the URL of the webapp and it is returning us the the same message which we wanted to receive.
    This clearly shows that our deployment is successfull.

    URL OF APPLICATION - flask-azurewebapp-assignment.azurewebsites.net
    by using the above url link we can access our application through browser.
![Screenshot_displaying_browser_output](C:\Users\syeds\OneDrive\Pictures\Screenshots\Screenshot2024-06-27154113.png)
