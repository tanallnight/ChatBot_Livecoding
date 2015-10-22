# ChatBot_Livecoding
Chatbot for livecoding.tv based off of the bot created by Cristy94 over here https://github.com/Cristy94/livecoding-chat-bot

# How to use
* First open chatbot.js and change the `MY_USERNAME` and `CURRENT_REPO` fields to your username and your github account or repo
* Open the chat in a new window, you can do that by accessing https://www.livecoding.tv/chat/username/, where `username` is your, well, username...
* Now open the JavaScript console (CTRL+SHIFT+J on Chrome) and paste the entire code from `chatBot.js` file into the it and press eter.
* The bot should now work as long as you keep the page opened.

# Features
### Admin commands
* You, as the bot runner, can write `!game start` or `!game stop` to start or stop a simple trivia game included.
* You can set any command as `key->value`. Example, setting the `repo` key:   
```
!set-website https://example.com  
!website
```
### General commands and features
* The bot will welcome people.
* `!leaderboard` to see the current leader of the game.
* `!time` will respond with the current time in the streamer's timezone.
* The bot will never interrupt you when writing.