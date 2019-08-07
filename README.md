# chatbot-server
Chatbot server developed in nodejs.

## Configuration 
You need to create .env file in the root directory with the ff. You can get the PAGE_ACCESS_TOKEN from your Facebook app settings. You can generate the VERIFY_TOKEN for your project. The VERIFY_TOKEN is used by the chatbot server to verify if the webhook request is coming from an authorized source which is your messenger bot.
```
PAGE_ACCESS_TOKEN=
VERIFY_TOKEN=
```

## Start the server
```
node server.js
```

## Deploying using Glitch
You can run the server code in glitch. It has been tested to be working fine. You can fork the repository in your github account and import the repo in glitch. Glitch is free hosting for nodejs code.

## Deploy using Docker
This is a work in progress
