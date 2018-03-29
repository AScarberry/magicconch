# magicconch

## For more information about the configuration and execution of this slack bot, visit https://api.slack.com/

You must create a config file for this bot to work. This ties the program execution from the server with the requests
and responses from the Slack API. The config file should be a JSON file and should look like this:
```
{
  "access_token": "",
  "scope": "",
  "team_name": "",
  "team_id": "",
  "clientID": "",
  "clientSecret": "",
  "bot": {
    "bot_user_id": "magic_conch",
    "bot_access_token": ""
  }
}
```

The values in the file will be given to you by slack when you install the bot.
Place this file in the same directory as the `index.js` file. 

## Setup and Installation

1. Install Node, and make sure you have NPM
2. Install Ngrok - https://ngrok.com/

### In order to run the app, navigate to the root of the project directory,
```
path/to/the/project/magicconch
```
run `npm install`. 

Once Ngrok and Node are successfully installed,
you should be able to run the app locally and have access to it through the Ngrok tunnel.

You can test Ngrok by typing 
```
ngrok http 8080
```
into the console.

You can test to see if the application works by typing( in the projects root directory),
```
node index.js
```

you should get a response that confirms it is listening on port.

