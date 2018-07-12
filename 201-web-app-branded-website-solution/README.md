# DigitalMarketing

Start simple with the content management system that enables you to easily maintain the messaging on your website in real-time, from a browser, with no coding skills.

## Deploy Components to Azure ##

1. Click the **Deploy to Azure** button.

   <a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F201-web-app-branded-website-solution%2Fazuredeploy.json" target="_blank">
     <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
   </a>

   <a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F201-web-app-branded-website-solution%2Fazuredeploy.json" target="_blank">
     <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png"/>
   </a>

2. Fill in the deployment settings.

   - **Resource group**: Recommended to create a new group.

   - **Name Prefix**: Provide the prefix name for all resources.

   - **Administrator Login**: Provide the admin login name for the database.

   - **Administrator Login Password**: Provide the admin login password for the database, it must meet the complexity requirements, e.g. `Jan232@18`

   - Check **I agree to the terms and conditions stated above**.

4. Click **Purchase**.

> **Note:** The static files (JS/CSS) hosted on CDN might not take effect immediately, so you might see the page layout of the newly created website is messing up until hours later.
