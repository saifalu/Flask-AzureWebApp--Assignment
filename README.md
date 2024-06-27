#Deploying Flask Application to Azure Web App using GitHub Actions
Tasks Performed
Directory and Environment Setup

Created a directory named Flask-AzureWebApp.
Activated a virtual environment for Python using venv.
Flask Application Development

Developed a Flask application (app.py) with a basic endpoint returning "Hello, Azure Web App with Flask!".
Dependency Management

Configured requirements.txt with necessary dependencies, including Flask.
GitHub Repository Setup

Created a GitHub repository named Flask-AzureWebApp-Assignment.
Initialized the repository, added files (app.py, requirements.txt), and pushed to GitHub.
Azure Web App Creation

Created an Azure Web App named flask-azurewebapp-assignment.
Configured the Azure Web App with Python 3.12 environment.
Deployment Configuration

Utilized Azure Portal's Deployment Center to link the GitHub repository (Flask-AzureWebApp-Assignment) for automated deployment.
Configured deployment settings to deploy from main branch.
Deployment Process

GitHub Actions Workflow (deploy.yml) configured for:
Setting up Python environment.
Installing dependencies (pip install -r requirements.txt).
Starting Flask application (flask run) with proper configuration.
Deploying to Azure Web App using Azure's webapps-deploy GitHub Action.
Verification and Access

Monitored GitHub Actions logs for successful deployment.
Accessed the deployed Flask application via the Azure Web App URL endpoint to verify functionality.
