# IP_Reporter-_bot
This python script use the Telegram API to send the changes in the public IP of the local machine. 

Requirements:
1. Create a bot in telegram (i.e. using @BotFather) and take the token.
2. Send a message to the bot through Telegram from the user/group that should receibe the bot's messages.
3. Make a post request to Telegram API with method getUpdates and take the chatid.
4. Put both, token and chatid, in the bot.py file, in the lines:
  token = "bot..." # Dont use separators between "bot" and the token, example: token = "bot123456789:AbCdEfGhIjKlMnOpQrStUvWxYz"
  chatID =         # Dont use "", put only the ID number, example: chatID = 123456789
5. Install python3 and python3-pip
6. install requests (pip3 install requests)
