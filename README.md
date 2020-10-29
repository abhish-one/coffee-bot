# Dialogflow-Chatbot
This project is aimed to show how to connect a dialogflow agent to your own customizable UI.

## Steps to run this chatbot(Deployed on Heroku)
1. Clone this repo
2. Find and run the index.html
3. Chat with the sample coffee-ordering bot.

## Steps to connect your own dialogflow bot
1. Make a Dialogflow agent (for simplicity use prebuilt agents)
2. Download the .json key-file and save it in the root folder
3. Replace the name of keyfile in app.js with your key-file name
4. Deploy this project on Heroku and make note of your heroku app url.
5. Change the url in fetchmsg() function in index.js to the heroku app url followed by send-msg endpoint
6. Run the index.html and start chatting with your bot in browser
7. If you don't want to deploy on heroku , then run the node app locally and replace the url by localhost url.
