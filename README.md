# Azure-Resource-Manager
deploy a web app using Azure Resource Manager

[resource](https://learn.microsoft.com/en-us/training/modules/create-deploy-azure-resource-manager-templates/6-create-deploy-resource-manager-template)

### Storage account created with ARM
<img width="1158" alt="image" src="https://user-images.githubusercontent.com/49791498/236444623-11f466d7-a90c-4140-8a19-4935e18b0b9f.png">


### App Service created with ARM
You have to manually deploy a Flask or Django app to the app service you just created.
Upload a zip of the codes, with

```Azure CLI
az webapp deployment source config-zip --resource-group <resource-group-name> --name <app-name> --src <path-to-zip-file>
```
<img width="1142" alt="image" src="https://user-images.githubusercontent.com/49791498/236466427-ee073e0f-13c1-4b38-a170-b7c0d087299b.png">
