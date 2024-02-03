# What is Azure Apps Service?
From your source code to worldwide availability, Azure Apps addresses the difficult difficulties. While you concentrate on designing your project, Azure Apps creates and hosts it using GitHub or Azure DevOps.

Azure App Service is a fully-managed platform by Microsoft that simplifies web app deployment and management. It supports multiple programming languages, offers automatic scaling for high traffic, and integrates smoothly with other Azure services. With easy deployment, continuous integration, and robust security features, developers can focus on creating exceptional web experiences while Azure takes care of the infrastructure and maintenance aspects. It's a launchpad for developers to bring their web projects to life with speed, reliability, and scalability—all in one place! 🚀

Azure App Service is like having your own personal launchpad for your web projects. It's a fully-managed platform provided by Microsoft that takes care of all the complex stuff, so you can focus on creating amazing experiences for your users.

## Here's what makes Azure App Service so awesome:

### Easy Deployment
It's as simple as uploading your web code or connecting it to a code repository like GitHub. No need to worry about server configurations or network settings. Just click a few buttons, and your app will be up and running in no time!

### Scalability 
Imagine your app goes viral, and thousands (or millions!) of users want to access it simultaneously. Azure App Service can handle the traffic spikes effortlessly. It automatically scales up or down based on demand, ensuring a smooth user experience for everyone.

### Supported Languages
Whether you love coding in C#, Java, Python, Node.js, or PHP, Azure App Service has got you covered. You can write your app in the language you're most comfortable with.

### Continuous Integration & Deployment (CI/CD)
This cool feature lets you automatically deploy your code changes whenever you push to your repository. It saves you time and reduces the risk of human errors during deployment.

### Security & Compliance
Azure takes security very seriously. It provides robust security features and compliance certifications, ensuring that your app and your users' data stay safe and protected.

### Integration with Other Azure Services
You can easily connect your app to other awesome Azure services like databases, storage, authentication, and more. It's like building a dream team of services to enhance your app's capabilities.

## Create the Azure App
You're a web developer who has developed a web app. A web app is often composed of HTML, JavaScript, or CSS files and can be developed manually or by using a framework.

Before you can deploy the app to Azure, you need to build it.

- Create a repository for your app on GitHub.
- Run the app locally and view it via a browser.

With the copy created locally, you’re all set to start working on your code and site. Now you’ll explore how to deploy your site to the cloud. You’ll use Azure Apps to host your site. Using Azure Apps Service will allow you to quickly post your web site to the world. You can explore more [Azure Tips and Tricks: Web Apps Service](https://learn.microsoft.com/en-us/shows/azure/app-service?wt.mc_id=studentamb_202028) to learn more. 

Next, open Azure portal by going on **https://azure.com/**.

` Note: If you don't have Azure free subscription, you can get free subscription by going on https://azure.microsoft.com/en-us/free/students from there you get 100$ credits`

1. Search for **Azure App Service** using searchbar.
![image](https://github.com/samipak458/Online-AI-Text-Translator/assets/52650290/31b8c995-f06b-4f5c-93ef-edeba7252421)

2. After clicking on it, you will see three options:
- Web App
- Static Web App
- Web App + Database

![image](https://github.com/samipak458/Online-AI-Text-Translator/assets/52650290/62310059-fec7-47ef-9d6f-241f4adffc7b)

3. Click on Web App as we're using another Azure service that is **Translator app service** in our web application.
4. Then it will ask about your project (web app) details.
- Select the subscription.
- Create new Resource group if don't created one before.
- Give a name to your web app.
- It ask for publish detail `select code` <br>
``` Note: If we migrating our static web app to web app then we select static web app ```.
- Then select runtime stack in our case it is **Python 3.11**.
- Then operating system, leave it default.
- Then select the region (While selecting region select the nearest region to your country).
- Then it ask for pricing plan `select Basic B1` pricing plan.
- Click on next deployment button after adding all the details.
  ![image](https://github.com/samipak458/Online-AI-Text-Translator/assets/52650290/d15c912f-1870-45f4-94a0-8076d94f91b1)
- Enable GitHub actions for continuous development.
![image](https://github.com/samipak458/Online-AI-Text-Translator/assets/52650290/2413dd73-636f-4053-b548-24b5212f594d)
- Then add your GitHub repo detail that you created for your web app.
![image](https://github.com/samipak458/Online-AI-Text-Translator/assets/52650290/ea442cd2-87fb-4e22-b5c2-a00c80263185)
- Then click on Review + create button. It is optional to edit network and monitor details in our case we don't need it.
![image](https://github.com/samipak458/Online-AI-Text-Translator/assets/52650290/55213b86-6320-4e02-b952-69226c77177c)
- Review all the details you added and click on **create** button.

It will take seconds in deploying your website. Then your website will be successfully deployed. You can see default domain (https://online-text-translator.azurewebsites.net/), click on it. 
![image](https://github.com/samipak458/Online-AI-Text-Translator/assets/52650290/d8d5f928-d11b-4e00-9f93-01fc17ab2dce)

You see the website is hosted on Azure App Service.
![image](https://github.com/samipak458/Online-AI-Text-Translator/assets/52650290/cf83e728-9a21-44b4-a5e3-74507ece5785)



### Note: If you want to host your static app which is build using framework then follow this [Publish an Angular, React, Svelte, or Vue JavaScript app with Azure Static Web Apps](https://docs.microsoft.com/en-us/learn/modules/publish-app-service-static-web-app-api/2-exercise-get-started?wt.mc_id=studentamb_202028)

## Resource
- Learn more about [Azure Apps Service](https://learn.microsoft.com/en-us/azure/app-service?wt.mc_id=studentamb_202028)
- Learn more Create & deploy [Azure Apps Service](https://learn.microsoft.com/en-us/shows/azure-demo-series/create-deploy-app-services?wt.mc_id=studentamb_202028)
- Learn about [Azure Static Web App Service](https://learn.microsoft.com/en-us/azure/static-web-apps?wt.mc_id=studentamb_202028)
