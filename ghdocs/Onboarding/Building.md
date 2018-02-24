# [sp-client](../../../README.md) › Building

This document describes how to setup your development environment to build the **office-ui-fabric-react** repository and contribute changes.

## Setup

- Make sure you have a **github** accont. If not, create one.
- Install **Node.js LTS 8** or greater from [Node.js website](https://nodejs.org/en/)

## Building

If you do not wish to contribute chages to the **office-ui-fabric-react** project, please follow the instructions on the [README](../README.md) page.

## Creating your own fork

If you wish to contribute changes back to the **office-ui-fabric-react** repository, start by creating your own fork of the repository. This is essential. This will keep the number of branches on the master repository to a small count. In your own fork, you can create as many branches as you like.

- Navigate to **[Github](https://www.github.com)** with a browser and login to your github account.
- Navigate to **[Office-ui-fabric-react](https://github.com/OfficeDev/office-ui-fabric-react)** repository in the same browser session.
- Click on the **fork** button at the top right corner of the page.
- Create the fork on your user name. Your github profile should now show **office-ui-fabric-react** as one of your repositories.
- Create a folder on your device and clone your fork of the **office-ui-fabric-react** repository. e.g. https://github.com/**manishgarg1**/office-ui-fabric-react.git. Notice how your github user name is in the repository location.
> git clone https://github.com/manishgarg1/office-ui-fabric-react.git

## Building

Next, clone and build the code.

- git clone https://github.com/manishgarg1/office-ui-fabric-react.git
- npm install
- npm run build
- npm start

## Setting up the upstream repository

Before starting to contribute changes, please setup your upstream repository to the primary **office-ui-fabric-react** repository.

- When you run **git remote -v**, you should see only your fork in the output list
>git remote -v

     origin  https://github.com/manishgarg1/office-ui-fabric-react.git (fetch)

     origin  https://github.com/manishgarg1/office-ui-fabric-react.git (push)

- Map the primary **office-ui-fabric-react** repository as the upstream remote
>git remote add upstream https://github.com/OfficeDev/office-ui-fabric-react.git

- Now running **git remote -v** should show the upstream repository also

     origin  https://github.com/manishgarg1/office-ui-fabric-react.git (fetch)

     origin  https://github.com/manishgarg1/office-ui-fabric-react.git (push)

     upstream        https://github.com/OfficeDev/office-ui-fabric-react.git (fetch)

     upstream        https://github.com/OfficeDev/office-ui-fabric-react.git (push)


- At this point you are ready to start branching and contributing back changes.

## Merging upstream master into your fork

At any point, when your fork will
## Creating a branch

