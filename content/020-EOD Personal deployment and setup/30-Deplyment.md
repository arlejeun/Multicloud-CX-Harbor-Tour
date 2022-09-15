---
title: "Azure EOD Personal deployment"
chapter: true
weight: 30
---

## Azure EOD Personal deployment
### Creating Your Configuration
 1. Go to the navigation in GDemo and select "Environments" from the Genesys Engage Cloud menu.
![Environments](/images/file_1604107212047_gecEnvironments.jpg)

 2. You will create a configuration and define the settings.
![Settings](/images/file_1604373858266_gecEODPersonalNew.jpg)


 4. Select Microsoft Azure as the Cloud Provider.
![Microsoft](/images/file_1622738616041_chooseAzureProvider.png)

 4. Select EOD Personal as the type of Environment that you want to provision, and then click "Create EOD Personal".
![Type](/images/file_1604372953844_gecEODPersonalType.jpg) 
 5. Complete the Properties page and click "Provision"..
![EODType](/images/file_1604374043471_gecEODPersonalType.jpg) 

 6. It may take a few minutes to provision. This is normal.
![PODRequested](/images/file_1604348078978_gecPOCRequested.jpg) 


### Provisioning Completed
 1. When finished, you will see your new Azure Personal EOD in your list of Live Environments.

![Done](/images/file_1604348160805_gecPOCSuccessful.jpg)


 2. Note the icon that designates your new EOD as provisioned on Azure.
 ![mylive](/images/file_1622738956387_myLiveAzure.png)

### Retrieving Configurations at later time
 1. At any time you can retrieve your configuration, such as Unit ID, agent password, etc., by going to 'My Live EODs', and then clicking the 'View EOD Configuration' icon.

![configuration](/images/file_1622739207774_viewNewEODConfig.png)
 2. On the Configuration page, note this button which will give you a PDF version of your configuration.
![pdf](/images/file_1604109897379_gecEODWorkshopPDF.jpg)
 3. Note that your Unit Type is designated as Azure.
![unit](/images/file_1622739397819_azureUnitType.png)


### Opening your Azure EOD Personal Portal ##

Once you have deployed your EOD Personal, open the Azure EOD Portal here:

[Azure EOD Portal](https://portal-1007-westus2.prod001.genesysengage.com/)

![Portal](/images/AzurePortal.PNG)


### Customization
Once you have created your Azure EOD Personal you can customize your environment. 
Additional setup instructions and information on supported channels is covered in Multicloud CX Workshop 102.

### Access Designer

Designer is a web-based tool for developing self-service (IVR) and assisted service (routing) applications that run on the Genesys Multicloud CX platform. It is an omnichannel solution, enabling you to craft applications that handle voice, chat, and email interactions.
You will learn how to create and customize designer application in Multicloud CX Workshop 102.
In this workshop we will learn how to access Desipgenr app and review Designer Analytics.

On the Azure EOD Portal login to Designer with your user of role Administrator (refer to 'Login Information' section on how to find users). 
> note: Tenant is left blank.


Designer Analytics is a powerful tool that provides a rich overview of your contact center operations. It features a series of informative dashboards, each of which offers a variety of visualizations and in-depth reporting panels that highlight specific aspects of your operations.

You can track calling trends, monitor how callers are interacting with the applications, and quickly notice and react to any potential issues with the applications or system platform. It can quickly answer questions you might have about your operations, such as:

How long are customers waiting for an agent?
How many customer interactions did we receive yesterday? Last week? Last month?
How many of our customers are contacting us from North America? Europe? Asia?
Key features:

- Almost real-time reporting means that as soon as an application session ends, Designer Analytics starts using the data to build reports.
Important
- 90-day data retention, so you can see how your applications are performing over time.
- Advanced filtering options, so you can focus on the data you want to see.

