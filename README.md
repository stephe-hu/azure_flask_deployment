# azure_flask_deployment
## App URL
https://stephen-504-flask.azurewebsites.net/
## Setting up the Application
1. Create a github repo named `azure_flask_deployment` that includes a README.md file. Find and copy the url of the repo.
2. Open up a Google Shell environment and in the terminal enter `git clone` and paste the repo url.
3. Open the folder and enter `cd` along with the folder name in the terminal to enter the folder.
4. Create a new folder named `data` to store the csv file.
5. Use the folder `flaskapp_0` in the `WK2` folder under the github repo `HHA_504_2023` as blueprint to set up the application by modifying the `app.py` file and the html files.
## Deployment to Azure
1. Enter the command `curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash` to install the Azure CLI.
2. Enter `az` to check that it is installed, then enter `az login --use-device-code` to connect to the Azure environment.
3. Follow the instruction in the terminal to sign in.
4. Enter the prompt `az webapp up --name <app-name> --runtime <PYTHON:3.9> --sku <B1>`, replacing the  `<app-name>` with your app name.
5. Enter `az webapp up` to redeploy it or push updates.