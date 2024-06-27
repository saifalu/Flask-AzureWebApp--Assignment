# Deploying *Flask Application* to *Azure Web App* using *GitHub Actions*

## Tasks Performed

### 1. Directory and Environment Setup
- Created our project directory named `Flask-AzureWebApp`.
- Activated a virtual environment for Python using `venv`.

#### Screenshots:
![Creating Directory and Virtual Environment](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/04c8586b-bbd7-4be3-bee3-c2ed1e2636a9)
![Activating Virtual Environment](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/1355d31a-041a-4cb5-a018-fa8a93b2da67)

### 2. Flask Application Development
- Developed a Flask application (`app.py`) with a basic endpoint returning "Hello, Azure Web App with Flask!".

#### Screenshot:
![Flask Application Code](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/36bfb69b-24e0-4aab-8c65-4b103f33d477)


### 3. Dependency Management
- Configured `requirements.txt` with necessary dependencies, including Flask.

#### Screenshot:
![Requirements.txt](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/2b586b00-8538-4ffd-b7cf-b87865944623)

### 4. Initialized the Git Repository and Pushed to GitHub
- Initialized the Git repository and added files (`app.py`, `requirements.txt`).
- Made the first commit and created a repository on GitHub named `Flask-AzureWebApp-Assignment`.
- Added the remote URL and pushed the code to GitHub.

#### Screenshot:
![Initializing Git and First Commit](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/01f50b29-01d9-4b98-b2fd-c85aba212aa8)
![Adding Remote and Pushing to GitHub](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/a60f7a9d-d012-4a84-a988-a39d7710b285)
![GitHub Repository](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/59a1cdb1-904e-46ce-9ce2-0d4718d4d119)

### 5. Azure Web App Creation
- Created an Azure Web App named `flask-azurewebapp-assignment`.
- Configured the Azure Web App with Python 3.12 environment in the Central India region.
- Selected Linux environment for deployment.

#### Screenshots:
![Creating Azure Web App](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/41b343da-268e-40fd-aab0-2bc6c17addf5)
![Configuring Azure Web App](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/56c92cbf-a0ea-405d-8428-78830569720b)
![Provisioned Azure Resource](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/24422ae2-860c-4b8a-8151-4ec5fc4e41be)

### 6. Deployment Configuration
- Utilized Azure Portal's Deployment Center to link the GitHub repository (`Flask-AzureWebApp-Assignment`) for automated deployment.
- Configured deployment settings to deploy from the master branch.

#### Screenshot:
![Deployment Center Configuration](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/3909f82e-ef56-41cb-8d4d-374d23eda0ec)

### 7. Deployment Process
- After saving the deployment settings, the deployment started using GitHub Actions to Azure Web App.
- Configured the GitHub Actions Workflow (`deploy.yml`) for:
  - Setting up Python environment.
  - Installing dependencies (`pip install -r requirements.txt`).
  - Starting Flask application (`flask run`) with proper configuration.
  - Deploying to Azure Web App using Azure's `webapps-deploy` GitHub Action.

#### Screenshots:
![GitHub Actions Deployment](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/3cfb142e-d38c-4908-9876-83d128294325)
![GitHub Actions Log](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/bb50bf51-4ba7-423c-bfc5-ea2928318583)
![Deployment Success](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/aa994e5c-4304-4b8e-b3fe-ec17ed95b967)

### 8. Verification and Access
- Monitored GitHub Actions logs for successful deployment.
- Accessed the deployed Flask application via the Azure Web App URL endpoint to verify functionality.

#### Screenshot:
![Deployed Flask App](https://github.com/saifalu/Flask-AzureWebApp--Assignment/assets/92035012/72e31bfb-bdd4-4024-a71f-6dc4ef0bd24b)

### URL of Application
Access the application using the following URL:
[flask-azurewebapp-assignment.azurewebsites.net](https://flask-azurewebapp-assignment.azurewebsites.net)

## Contact Information
- **Developed & Deployed by:** **Syed Saif Ali**
- **Phone:** 8957204383
- **Email:** [syedsaifali214@gmail.com](mailto:syedsaifali214@gmail.com)
- **LinkedIn:** [linkedin.com/in/--saif](https://www.linkedin.com/in/--saif/)


