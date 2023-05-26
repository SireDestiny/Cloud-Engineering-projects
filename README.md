# Cloud-Engineering-projects
These are some of the Cloud Engineering projects that I have completed.

  Plan Agile with GitHub Projects and Azure Boards: Link: https://dev.azure.com/ogunleretomi/Agile%20Planning%20and%20Portfolio%20Management%20with%20Azure%20Boards/_workitems/recentlyupdated/
  - Tools: Azure DevOps Organization, Azure DevOps Server
  - Aim: Agile process of planning, managing and tracking work across the entire team.
  - This work entails working with GitHub projects, GitHub projects boards and Azure boards. 
  - Explored ways to configure, manage and integrate Azure boards and Github.
  - Customized project view, and explored collaboration using team discussions.
  - Managed teams, areas and iterations.
  - Managed work items, sprints and capacity.
  - Defined dashboards, Kanban boards, and customized team processes.


Version Controlling with Git in Azure Repos: 
link: https://dev.azure.com/ogunleretomi/Version%20Controlling%20with%20Git%20in%20Azure%20Repos/_git/PartsUnlimited/pushes?itemVersion=GBmaster
- Tools: Git, Visual Studio Code, PowerShell, Source Control, GitLens, Git History, C#, Azure DevOps Server, Azure DevOps Organization.
- This project involves working with Git distributed version control system, branches, repositories, and source control.  
- It involves integrating changes from the local environment in Visual Studio Code to the Server side in Azure DevOps.
- I imported a Git repository into my Azure DevOps project.
- I cloned the imported repository from the Azure DevOps server to Visual Studio code in my local machine.
- Saved work with commits.
- Pushed changes to branches and merged branches.
- Established branch policies for code quality and change-management standards.
- Created, approved, completed pull requests, and completed merges.
- Applied tags to the repository. 


Integrating External Source Control with Azure Pipelines: Azure devops link - https://dev.azure.com/ogunleretomi/Integrating%20External%20Source%20Control%20with%20Azure%20Pipelines/_build?definitionId=10 
 GitHub link https://github.com/actionsdemos/calculator/compare/master...SireDestiny:calculator:master
- Tools: GitHub, Azure Pipelines (CI/CD), Azure DevOps Organization.
- This project was hosted on GitHub. 
- Used Azure pipeline integration to integrate the GitHub project and Azure DevOps.
- Installed Azure pipelines from the GitHub marketplace. 
- Configured the Azure Pipelines in Azure the DevOps server.
- Forked a GitHub repository into the Azure DevOps project.
- Proposed a change via GitHub pull request.
- Tracked pull requests through the pipeline.
- Added a status badge to my GitHub Repo.


Configuring Pipelines as Code with YAML: https://dev.azure.com/ogunleretomi/Configuring%20Pipelines%20as%20Code%20with%20YAML/_build/results?buildId=20&view=results
- Tools/ Tags: Azure Portal, Bash Scripting, YAML, CI, CD.
- This project aimed to define build and release pipelines using YAML.
- Created Azure resources such as resource group, App service plan from the Azure portal.
- Configured CI/CD as code with YAML in Azure DevOps. 
- Added a YAML build definition, added continuous delivery to the YAML definition


Controlling Deployments using Release Gates: https://dev.azure.com/ogunleretomi/Controlling%20Deployments%20using%20Release%20Gates/_releaseProgress?_a=release-pipeline-progress&releaseId=1
Tools/ Tags: Azure subscription, Azure DevOps Organization, Resource Group,  Azure App Service, Cloud Shell, Bash scripting,  CI/CD,  
- This project was hosted on GitHub. 
- Azure pipeline integration was utilized to integrate the GitHub project and Azure DevOps.
- With bash scripting from Azure portal, I created a Resource Group, App Service plan, and two Azure webapps environments i.e. Canary and Production environments.
- Configured an Application insight resource for the Canary web app.
- Created a monitoring alert by setting alert rules for failed requests. 
- Configured a build pipeline to generate a build artifact. 
- Configured a release pipeline to deploy the application to Azure App Service.
- I configured the release gates to set pre-deployment gates for approvals and set the post-deployment gate for Azure Monitor.


Deploying Docker containers to Azure App Service web apps: https://dev.azure.com/ogunleretomi/Deploying%20Docker%20containers%20to%20Azure%20App%20Service%20web%20apps_/_release?_a=releases&view=mine&definitionId=1
- Tools/ Tags: Azure subscription, Azure DevOps Organization, Resource Group,  Azure App Service, Cloud Shell, Bash scripting,  CI/CD,  Docker
- This project used the Azure DevOps CI/CD pipeline to build a Docker image, pushed it to Azure Container Registry, and deploy it as a container to Azure App Service.
- Set up a service connection with my Azure subscription using Service Principal (Manual)
- Imported and ran CI pipeline.
- Added a role assignment to allow Azure App Service to pull the docker image from Azure Container Registry. 
- I imported and ran a CD pipeline.


Implementing GitHub Actions for CI/CD
Link: (https://github.com/SireDestiny/-eShopOnWeb/actions)
- This project was done to implement a GitHub workflow for CI/CD that deploys an Azure web app using DevOps starter.
- Tools/ Tags: Azure subscription, Cloud Shell, Bash scripting, GitHub, GitHub Actions, CI/CD, Resource Group, Azure Service Plan, App Service.
- Imported an existing repository into a newly created repository in my GitHub account. 
- Modified the GitHub workflow to trigger on every push to the master branch.  
- The workflow runs jobs such as build, test and publish. Then, it uploads the bicep template as artifacts. 
- It uses bicep to deploy infrastructure and publish a webapp. 
- It downloads published files and bicep templates, and it logs in to Azure to deploy the webapp. 
- Finally, it publishes the website to Azure App Service (WebApp).


Setting Up and Running Functional Tests: https://dev.azure.com/ogunleretomi/Setting%20Up%20and%20Running%20Functional%20Tests/_releaseProgress?_a=release-pipeline-progress&releaseId=1


Enabling Continuous Integration with Azure Pipelines: https://dev.azure.com/ogunleretomi/Enabling%20Continuous%20Integration%20with%20Azure%20Pipelines/_build/results?buildId=8&view=results


Configuring Agent Pools and Understanding Pipeline Styles: https://dev.azure.com/ogunleretomi/Configuring%20Agent%20Pools%20and%20Understanding%20Pipeline%20Styles/_build/results?buildId=31&view=logs&j=fd490c07-0b22-5182-fac9-6d67fe1e939b
