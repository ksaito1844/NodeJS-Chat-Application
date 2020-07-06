# Chat App created using NodeJS and Socket.IO and hosting on Azure
This is a tutorial on how to setup a basic chat app using NodeJS and Socket.IO and deploying and hosting it successfully on Azure.

This basic app is a sample for a group chat which can have multiple participants and offers a place where these participants can chat.

The app is hosted on Azure at 
```
http://nodegroupchat.azurewebsites.net/
```
This repository can be used for learning purpose the same way i did.

If you have any query regarding this repository, I would be happy to reply back. You can connect with me on [LinkedIn](https://www.linkedin.com/in/avichel-verma/)
## Getting Started
The following technologies are used:
- Visual Studio Code (Code Editor of choice)
- NodeJS
- Socket.io

## Installation Guide
This installation guide is for Windows. But Mac and Linux can follow too for basic installation.
- Install Visual studio code or any code editor of choice.(The reason of choosing VS code is because of it's integration with Azure)
- Install [NodeJS](https://nodejs.org/en/) (install the LTS version for nodejs)

## Folder Structure for the application
- /root
-- public (contains all html, css and javascript code)
-- index.js (contains the server-side code)

## Setting up the app
Once you have successfully installed NodeJS. To create the index.js, we are going to use the command
```
npm init
```
You can either select the default values or enter your add your own if you want to change.

Now, index.js will be created. Create a folder named public and create three files namely index.html, main.js and style.css

To install socket.io, run the command
```
npm install socket.io
```

You can also fork this repo and clone it to your pc locally.
If you clone this repository, run this command to install the necessary dependencies.
```
npm install
```

### Runthe server locally
Go to the /src folder for this application and run this command.
```
node index.js
```
Your app url is hosted on ```localhost:3000```.
Go to your browser of choice and go to the app url.

Enjoy chatting with your friends on your local devices by opening multiple browsers.

### Steps to deploy this app to Azure

Firstly, install [Azure App Serive](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azureappservice)

- Follow these [steps](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-get-started-nodejs#deploy-the-app-to-azure) to deploy the app to Azure.

- Follow the steps mentioned above to successfully create a CI/CD pipeline and deploy the app azure.

Note:
The reason for attaching the steps guides is for easy understanding with Microsoft docs and it is maintained by Microsoft making it more trustable.

# Author
- This guide is created by Avichel Verma
- Main credits goes to Socket.io and Microsoft docs for their exceptionally guides.













