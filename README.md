# Setting up CICD for an Orchard Core CMS Web Application using Azure Dev Ops

Setting up CICD for an Orchard Core CMS Web Application using Azure Dev Ops

## Automating the Build Process

## YouTube Video

[![OrchardSkillsYouTubeThumbNailCICD](https://user-images.githubusercontent.com/59172485/90349375-dcf1bb80-dff6-11ea-96aa-c588416b846d.png)](https://youtu.be/8cQLcDFJvvA)

# Introduction

Incorporating automation into the end-to-end software development pipeline improves consistency and efficiency. Implementing Continuous Integration and Continuous Delivery is essential for productivity. So, let's started by creating a CICD pipeline for an Orchard Core CMS Web Application using Azure DevOps.

# Getting Started

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-000](https://user-images.githubusercontent.com/59172485/90348530-bc743200-dff3-11ea-961d-dc6a20875dee.png)

One of the best places to get started with developing with Microsoft tools is Visual Studio Dev Essentials:
https://visualstudio.microsoft.com/dev-essentials/

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-001](https://user-images.githubusercontent.com/59172485/90348531-bd0cc880-dff3-11ea-8323-14b958c84347.png)

Sign in with your Microsoft account.



![CICD-Orchard-Core-CMS-Azure-Dev-Ops-002](https://user-images.githubusercontent.com/59172485/90348532-bd0cc880-dff3-11ea-9609-d713c7de1f45.png)

Enter your password.



![CICD-Orchard-Core-CMS-Azure-Dev-Ops-003](https://user-images.githubusercontent.com/59172485/90348533-bda55f00-dff3-11ea-83fa-fe3f736f50e7.png)



Select Azure DevOps.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-004](https://user-images.githubusercontent.com/59172485/90348534-bda55f00-dff3-11ea-9c33-c3582a0bb578.png)



Fill in your information.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-005](https://user-images.githubusercontent.com/59172485/90348535-bda55f00-dff3-11ea-91c0-0d6480d45c76.png)



Lets get started setting up your account. Press the "Create a new organization" button.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-006](https://user-images.githubusercontent.com/59172485/90348536-be3df580-dff3-11ea-824f-9d73e770bac3.png)



Click the checkbox if you want to help Microsoft to collect data to make Azure DevOps better. Press the "Continue Button".

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-007](https://user-images.githubusercontent.com/59172485/90348537-be3df580-dff3-11ea-9aa3-c1a8c1d39f79.png)



Enter organization and location.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-008](https://user-images.githubusercontent.com/59172485/90348538-be3df580-dff3-11ea-9981-b583bb83d6af.png)

Select either public or private visibility.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-009](https://user-images.githubusercontent.com/59172485/90348539-bed68c00-dff3-11ea-9ac5-65056bb409b9.png)



Azure DevOps is now setup.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-010](https://user-images.githubusercontent.com/59172485/90348540-bed68c00-dff3-11ea-9b82-75e833a09d3c.png)

Go pack to the Visual Studio Dev Essentials page:

https://visualstudio.microsoft.com/dev-essentials/

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-011](https://user-images.githubusercontent.com/59172485/90348541-bed68c00-dff3-11ea-8b10-f5c13f6c4998.png)



Select Azure.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-012](https://user-images.githubusercontent.com/59172485/90348542-bf6f2280-dff3-11ea-82d7-cc7781975755.png)



Fill out the information.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-014](https://user-images.githubusercontent.com/59172485/90348544-c007b900-dff3-11ea-9422-d8e6fe3fd5d6.png)



More Information to fill out.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-015](https://user-images.githubusercontent.com/59172485/90348545-c007b900-dff3-11ea-95bb-a266ea8b3edf.png)



Fill out your credit card information.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-016](https://user-images.githubusercontent.com/59172485/90348546-c007b900-dff3-11ea-9222-3864b884f9de.png)

Agree to the customer agreement and privacy agreement.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-017](https://user-images.githubusercontent.com/59172485/90348547-c0a04f80-dff3-11ea-8ad5-367045bc5283.png)



Click next.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-018](https://user-images.githubusercontent.com/59172485/90348548-c0a04f80-dff3-11ea-9d5a-29565b8969f0.png)



No need for Technical support. We can figure it out.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-020](https://user-images.githubusercontent.com/59172485/90348550-c0a04f80-dff3-11ea-8685-5ef5ea1ee6ac.png)



Cleck on "Start tour" to start learning.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-022](https://user-images.githubusercontent.com/59172485/90348551-c138e600-dff3-11ea-9f41-a2a030ed6c22.png)

Select Subscription.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-023](https://user-images.githubusercontent.com/59172485/90348552-c138e600-dff3-11ea-9031-5e6d5c5cc2bd.png)



Select Azure subscription 1.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-024](https://user-images.githubusercontent.com/59172485/90348553-c138e600-dff3-11ea-9562-e1ee8bb2f8e3.png)



Click on Rename.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-025](https://user-images.githubusercontent.com/59172485/90348554-c1d17c80-dff3-11ea-9baf-4bdee838baae.png)

Enter a better name for you subscription. Use something like your organization. I used OrchardSkills.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-026](https://user-images.githubusercontent.com/59172485/90348555-c1d17c80-dff3-11ea-8639-e73fc09c0e03.png)

In the search edit box type "DevOps Project".

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-027](https://user-images.githubusercontent.com/59172485/90348556-c1d17c80-dff3-11ea-836d-e506dcfe3c8b.png)

Press "Create DevOps Project" button.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-028](https://user-images.githubusercontent.com/59172485/90348557-c1d17c80-dff3-11ea-851d-b93769a35167.png)

Select ".NET".

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-029](https://user-images.githubusercontent.com/59172485/90348558-c26a1300-dff3-11ea-9847-86a7ec2c18e6.png)



Select ASP.NET Core.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-030](https://user-images.githubusercontent.com/59172485/90348559-c26a1300-dff3-11ea-9684-1dd75addff44.png)

Select Linux Web App.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-031](https://user-images.githubusercontent.com/59172485/90348560-c26a1300-dff3-11ea-9d17-96d9681e8056.png)

Fill out the information.  Type in a project name and select the pull down combo items relevant. 

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-032](https://user-images.githubusercontent.com/59172485/90348562-c302a980-dff3-11ea-80d6-eaf369cfdd7e.png)

Wait for deployment to complete then press go to resource.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-033](https://user-images.githubusercontent.com/59172485/90348563-c302a980-dff3-11ea-88a3-3b0edfe95be4.png)



Your CICD pipeline will start.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-034](https://user-images.githubusercontent.com/59172485/90348564-c302a980-dff3-11ea-8945-74a23e81729a.png)

After a successful build deployment your site is ready.

![CICD-Orchard-Core-CMS-Azure-Dev-Ops-035](https://user-images.githubusercontent.com/59172485/90348565-c39b4000-dff3-11ea-9f0c-d0def4cdea0d.png)



![](https://user-images.githubusercontent.com/59172485/89642476-2d3b8180-d871-11ea-80d2-89f922919135.png)

After the build and deployment process is successful you can visit the Azure Website URL at: https://orchardskills.azurewebsites.net/ 

![](https://user-images.githubusercontent.com/59172485/89642478-2d3b8180-d871-11ea-8d89-6573ac9c1df5.png)

Go to the App Service page by selecting on the App Service resource link.

![](https://user-images.githubusercontent.com/59172485/89642479-2d3b8180-d871-11ea-8d9a-eda2ea2b2a5b.png)

Select the desired App Service Plan. Select Dev/Test B1 and select apply.

![](https://user-images.githubusercontent.com/59172485/89642480-2dd41800-d871-11ea-8ee0-47cc8d560c45.png)

Go to the Azure Dev Ops
https://dev.azure.com/OrchardSkills/

Select the OrcardSkills project by clicking on the OrchardSkills link.

![](https://user-images.githubusercontent.com/59172485/89642483-2dd41800-d871-11ea-89c6-7ceb6c137fa9.png)

Click on "Pipelines" located on the left side menu.

![](https://user-images.githubusercontent.com/59172485/89642484-2dd41800-d871-11ea-9cb9-6d7be3e078d0.png)

Click on "OrchardSkills - CI" pipeline.

![](https://user-images.githubusercontent.com/59172485/89642485-2e6cae80-d871-11ea-90a2-4e1d8752cefe.png)

Click on the "Edit" button.

![](https://user-images.githubusercontent.com/59172485/89642486-2e6cae80-d871-11ea-80b0-8462d62d2372.png)

These are the build pipeline steps to compile and publish the artifact to the Releases (OrchardSkills - CD).

![](https://user-images.githubusercontent.com/59172485/89642487-2e6cae80-d871-11ea-8a7d-c25c2bc96668.png)

Delete the "Test" step.

![](https://user-images.githubusercontent.com/59172485/89642488-2f054500-d871-11ea-8f1f-4ebed972901a.png)

Delete the "Publish functional tests" step.

![](https://user-images.githubusercontent.com/59172485/89642490-2f054500-d871-11ea-9597-b313195defb6.png)

Delete the "Copy runsettings file" step.

![](https://user-images.githubusercontent.com/59172485/89642491-2f9ddb80-d871-11ea-89de-5f32cfefe9e2.png)

Delete the "Copy ARM templates" step.

![](https://user-images.githubusercontent.com/59172485/89642492-2f9ddb80-d871-11ea-8bce-aa80463b182b.png)

Select the "Get sources".

![](https://user-images.githubusercontent.com/59172485/89642495-2f9ddb80-d871-11ea-825c-3fa40d50bded.png)

Select GitHub.

![](https://user-images.githubusercontent.com/59172485/89642496-30367200-d871-11ea-84d6-b12d4b853bd7.png)

Click on the Repository "..." button.

![](https://user-images.githubusercontent.com/59172485/89642497-30367200-d871-11ea-951f-dc0c7c7e246e.png)

Select the "OrchardSkills/OrchardSkill.OrchardCore.CICD" repository.

![](https://user-images.githubusercontent.com/59172485/89642498-30cf0880-d871-11ea-93c4-845cdb72a5e0.png)

Confirm GitHub seetings

![](https://user-images.githubusercontent.com/59172485/89642502-31679f00-d871-11ea-8db2-1b333ae033c8.png)

Select "Feeds in my NuGet.config" radio button and select the file in the repository.

![](https://user-images.githubusercontent.com/59172485/89642499-30cf0880-d871-11ea-8cef-0e9a5fc93091.png)

Save and queue.

![](https://user-images.githubusercontent.com/59172485/89642500-30cf0880-d871-11ea-8475-97d673ee5b0d.png)

Press "Save and run" button.

![](https://user-images.githubusercontent.com/59172485/89642501-31679f00-d871-11ea-88c9-b0478c87e90e.png)

Monitor the build process.

![](https://user-images.githubusercontent.com/59172485/89642503-31679f00-d871-11ea-8186-36871f9007ce.png)

The build fails because its trying to create an existing app service and also there are multiple dll files in the artifact and it does not know which one to deploy.

![](https://user-images.githubusercontent.com/59172485/89642505-32003580-d871-11ea-9d15-e2de356e267e.png)

Select the "Edit Release" drop down.

![](https://user-images.githubusercontent.com/59172485/89642506-3298cc00-d871-11ea-85ac-ec5255dacb21.png)

Click on the "1 job, 2 tasks" link

![](https://user-images.githubusercontent.com/59172485/89642507-3298cc00-d871-11ea-85df-8c09f6b62852.png)

Click on the "View stage tasks".

![](https://user-images.githubusercontent.com/59172485/89642508-3298cc00-d871-11ea-80de-a8d94ee3609e.png)

Remove the "Azure Deployment Create Azure App Service" by right clicking on the task.

![](https://user-images.githubusercontent.com/59172485/89642509-33316280-d871-11ea-9271-03de72851bbc.png)

Click on the Package or folder (File path to the package or a folder containing app service contents) The path should be as follows:
$(System.DefaultWorkingDirectory)/Drop/drop/OrchardSkills.OrchardCore.OrchardSkills.zip

![](https://user-images.githubusercontent.com/59172485/89642510-33316280-d871-11ea-8120-8cd8251d038d.png)

Save and create a new release.

![](https://user-images.githubusercontent.com/59172485/89642511-33c9f900-d871-11ea-80ff-8811cea3ce77.png)

Click on the "Create" button.

![](https://user-images.githubusercontent.com/59172485/89642512-33c9f900-d871-11ea-8e7a-4a3963e1d24b.png)

Build deployed successfully.

![](https://user-images.githubusercontent.com/59172485/89642513-33c9f900-d871-11ea-97ab-70c4f73b37d0.png)

Go back to the Azure portable and select create a SQL database. https://portal.azure.com/ Click on the "Create SQL database" button.

![](https://user-images.githubusercontent.com/59172485/89642514-34628f80-d871-11ea-8ea5-7f3d4be51ba3.png)

Create a new Database server by selecting a name, entering in the credentials and pressing the "OK" button.

![](https://user-images.githubusercontent.com/59172485/89642516-34628f80-d871-11ea-9475-82e1bb7f530b.png)

Select the desired database tier Basic. 

![](https://user-images.githubusercontent.com/59172485/89642517-34fb2600-d871-11ea-84cf-2303dd9316ff.png)

Click on the "Review + create" button.

![](https://user-images.githubusercontent.com/59172485/89642518-34fb2600-d871-11ea-92ef-cb4c8948272d.png)

Click on the "Create" Button.

![](https://user-images.githubusercontent.com/59172485/89642519-34fb2600-d871-11ea-9e83-eff9127cc035.png)

Wait for the database to be deployed and then press on the "Go to resource" button.

![](https://user-images.githubusercontent.com/59172485/89642521-3593bc80-d871-11ea-93cc-8f442bf5c2b4.png)

Click on the "Set server firewall" link.

![](https://user-images.githubusercontent.com/59172485/89642524-3593bc80-d871-11ea-877b-79ab2a78b1ae.png)

Click "Yes" on Allow Azure services and resources to access this server.

![](https://user-images.githubusercontent.com/59172485/89642526-362c5300-d871-11ea-98eb-10286014b85c.png)

Go to the Azure Website URL
https://[enter-your-site-here].azurewebsites.net/

Orchard Core is running!

# Conclusion

Once you have CICD setup, Any changes to your repository will trigger the build and deployment process.

# GitHub

The complete source code is located [here](https://github.com/OrchardSkills/OrchardSkills.OrchardCore.CICD).