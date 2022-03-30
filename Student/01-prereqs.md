# Challenge 1: Pre-requisites & Setup - Ready, Set, GO! 

**[Home](../README.md)** - [Next Challenge >](02-acr.md)

## Introduction

A smart cloud solution architect always has the right tools in their toolbox. 

## Description

In this challenge we'll be setting up all the tools we will need to complete our challenges.

### Local tooling
- Make sure that you have joined the Teams group for this hack and found your channel. 
- Install the recommended toolset: (assumes Windows)
    - Windows Subsystem for Linux
    - Azure CLI
    - Kubectl (kubernetes CLI)
    - Visual Studio Code.  Recommended extensions:
      - [Azure Account](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account)
      - [Kubernetes](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools)
- These tools could also be run on MacOs, or alternatively, you could use the Azure Cloud Shell

### Azure

Your coach will provide an Azure Pass code for your team to use during the hack. Set it up as follows:
1. Someone on the team needs to volunteer to set up the pass.  This person **must** use a [Microsoft accoount](https://account.microsoft.com/account) to configure the pass; you cannot use a corporate account.  
2. For this step we ***strongly*** recommend using an incognito/in-private browser window, or alternatively a new browser profile:  Using the designated Microsoft account, go to https://www.microsoftazurepass.com/ and enable the Azure pass, which will create a new Azure subscription.
3. Next, we will add the rest of the team as co-owners of the new subscription:  Visit https://portal.azure.com, find the Subscription that was created, and add the Microsoft Account ids of the rest of the team (and your coach!) as co-owner on the subscription

### Code Sharing

While not 100% required, it is highly recommended that the team set up a repo to share code, manifests, snippets, etc.  Feel free to use your preferred source code control system:  GitHub, Azure DevOps, GitLab, etc.


## Success Criteria

1. You have a bash shell at your disposal (WSL, Mac, Linux or Azure Cloud Shell)
1. Running `az --version` shows the version of your Azure CLI
1. Visual Studio Code is installed.
2. Everyone is enabled as a co-owner on the new Azure Subscription
