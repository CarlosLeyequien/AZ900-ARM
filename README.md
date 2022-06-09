# AZ900-ARM
Usage of Azure ARM

  1) Go to the Resource, scroll down in the left hand column down to the "Automation" sub-menu and click on "export template"

  ![image](https://user-images.githubusercontent.com/105960409/172737178-bf53563d-7b63-444f-8ec3-183d6ee7f720.png)

  2) That will export the code for the resource, which can be downloaded

  ![image](https://user-images.githubusercontent.com/105960409/172737273-63cb2321-eb9b-4102-9aa3-514a20e5afba.png)

  3) To upload your own ARM template, you need to code it and save it as a json file

  ![image](https://user-images.githubusercontent.com/105960409/172738661-d33de229-bde8-4406-83d0-c68f31d134a3.png)

  4) Go to the folder where the json is created and open a CMD window there(Type cmd in the address bar) and enter the following command

    az deployment group create --name (your template name) --resource-group (resource group name) --template-file (template name with .json)
    
   ![image](https://user-images.githubusercontent.com/105960409/172738591-4e2103f1-2496-4cb2-8424-ab78c07bfecd.png)

  5) Once it finishes, if the deployment was correct, it will show a success message

  ![image](https://user-images.githubusercontent.com/105960409/172738762-ec0ac65c-4842-4fd6-af87-f8a71d9f1384.png)

  6) Click on the "deployments" sub-menu on the left side column of the resource, your depoyment will appear in the content viewer:

  ![image](https://user-images.githubusercontent.com/105960409/172738918-44ffe9ec-ecee-486c-aec5-b9b62b13e628.png)

  7) When you click on the deployment it will show you the status and you can see your deployment code

  ![image](https://user-images.githubusercontent.com/105960409/172738989-e2ab9c46-989f-4007-a246-012058d47e44.png)

  ![image](https://user-images.githubusercontent.com/105960409/172739042-8b6f1a2a-0647-48d6-ab6b-7cdb2ac91753.png)

    Example of the code for a storage account
   ![image](https://user-images.githubusercontent.com/105960409/172739538-0032e3c9-f265-4af3-840d-9e875b91bb10.png)

  
