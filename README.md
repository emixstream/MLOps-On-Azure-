# MLOps-On-Azure-

### During the Technological Infrastructure for Data Science course, my team and I decided to explore the interesting topic of Machine Learning Operation (MLOps).

### In this repo you will find the presentation of the topic and the code that was used to reproduce a deployment on the Microsoft Azure infrastructure. Doing this was possible thanks to the guidance of Srijith, who held a webinar on the topic and released the code that was used for this demo.

### Many Thanks to Srijith for this amazing tutorial:

I copy-paste here his README.md 

(https://www.youtube.com/watch?v=pLd7xF0z5Zs)

# Introduction 
Fully Automated end-to-end Training and Deployment of IRIS Classifer using Azure MLOps
# Prerequisites
1. Azure [Account] (https://azure.microsoft.com/en-in/free/search/?&ef_id=EAIaIQobChMIhIHs3_Ca7wIVI4ZLBR0yKQsDEAAYASAAEgLhFvD_BwE:G:s&OCID=AID2100054_SEM_EAIaIQobChMIhIHs3_Ca7wIVI4ZLBR0yKQsDEAAYASAAEgLhFvD_BwE:G:s)
2. Understanding of [Azure DevOps](https://azure.microsoft.com/en-in/services/devops/)
# Getting Started
1.	Read more about [Azure MLOps](https://azure.microsoft.com/en-in/services/machine-learning/mlops/)

# Azure DevOps Instructions
1. Create a Code Repo/Link git repos
2. Create a Project named MLOpsIRIS
3. Create a Service Connection ( This will be used in Build and Deploy pipelines). Project Settings --> Service Connections --> New Service Connections --> Azure Resource Manager 

# Build & Deploy Steps
1. Build steps can be found in CLI Commands/Build direectory
2. Deployment steps can be found in CLI Commands/Deploy direectory
