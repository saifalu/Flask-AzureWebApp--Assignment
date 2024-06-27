# Deploying Flask Application to Azure Web App using GitHub Actions

# Tasks Performed
## 1. Directory and Environment Setup
     Created our project directory named Flask-AzureWebApp.
     Activated a virtual environment for Python using venv.
    these screenshots dhows the used command - 
![Screenshot2024-06-27145637](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/04c8586b-bbd7-4be3-bee3-c2ed1e2636a9)

![Screenshot2024-06-27150642](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/1355d31a-041a-4cb5-a018-fa8a93b2da67)

## 2. Flask Application Development
  I Developed a Flask application (app.py) with a basic endpoint returning "Hello, Azure Web App!".
  The screenshot shows the written code for application-
  ![Screenshot2024-06-27153151](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/36bfb69b-24e0-4aab-8c65-4b103f33d477)


![Screenshot2024-06-27150432](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/4297a3d3-3bbe-4a1a-ab1f-c238c23390d6)

## 3. Dependency Management
    I have Configured requirements.txt with necessary dependencies, including Flask by.
![Screenshot2024-06-27150432](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/2b586b00-8538-4ffd-b7cf-b87865944623)


![Screenshot2024-06-27150817](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/b041183e-428b-4c8e-9f72-c21c5a0aafc3)


## 4. Initialized the Git repository, added files (app.py, requirements.txt) and made our first commit 
    I initialized our git repository and added files into it and made our first commit. then I created a repository at Github and added its remote url.
    Note : the github repository is shown in next step.
![Screenshot2024-06-27150833](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/01f50b29-01d9-4b98-b2fd-c85aba212aa8)

![Screenshot2024-06-27150933](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/a60f7a9d-d012-4a84-a988-a39d7710b285)

![Screenshot2024-06-27151102](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/366e88da-224c-45bd-8e28-e4152c07b0e1)


## 4. GitHub Repository Setup
    Created a GitHub repository named Flask-AzureWebApp-Assignment.In this repository we have pushed our application files.

![Screenshot2024-06-27151142](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/59a1cdb1-904e-46ce-9ce2-0d4718d4d119)


![Screenshot2024-06-27151206](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/b104bda6-6268-4634-a0ef-9346f9ac5b83)

## 6. Azure Web App Creation
   Created an Azure Web App named flask-azurewebapp-assignment.
   Configured the Azure Web App with Python 3.12 environment.
   I have created this WebApp in Central India region.
   I have selected Linux envrionment in which we will be deploying our application in next steps.
 ![Screenshot2024-06-27151410](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/41b343da-268e-40fd-aab0-2bc6c17addf5)

![Screenshot2024-06-27151424](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/56c92cbf-a0ea-405d-8428-78830569720b)


   thus we have created our webapp and the provisioned resource is shown in the image

![Screenshot2024-06-27151530](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/24422ae2-860c-4b8a-8151-4ec5fc4e41be)



## 7. Deployment Configuration
    Utilized WebApp's Deployment Center to link the GitHub repository (Flask-AzureWebApp-Assignment) for automated deployment.
    Configured deployment settings to deploy from master branch.

![Screenshot2024-06-27151607](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/3909f82e-ef56-41cb-8d4d-374d23eda0ec)



## 8. Deployment Process
    After clicking on save button shown in above image, our deployment started from Github Actions to Azure WebApp using CI/CD methos.
    These screenshots shown the deployment procedure-
![Screenshot2024-06-27152317](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/3cfb142e-d38c-4908-9876-83d128294325)
![Screenshot2024-06-27152402](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/bb50bf51-4ba7-423c-bfc5-ea2928318583)

![Screenshot2024-06-27170138](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/aa994e5c-4304-4b8e-b3fe-ec17ed95b967)

![Screenshot2024-06-27152753](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/1b85933b-13ae-4229-b4d6-f53e36d74051)




## 9. Verification and Access
    
    After successfull deployment of our flask application into Azure WebApp , I have visited the URL of the webapp and it is returning us the the same message which we wanted to receive.
    This clearly shows that our deployment is successfull.

    URL OF APPLICATION - flask-azurewebapp-assignment.azurewebsites.net
    by using the above url link we can access our application through browser.
![Screenshot2024-06-27154113](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/72e31bfb-bdd4-4024-a71f-6dc4ef0bd24b)

