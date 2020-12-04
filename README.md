# RestaurantChatBot
 Restaurant Chat Bot built using Zomato API and RASA Framework
Prerequisites
1. Zomato API Key
2. Rasa Framework

How to use
Clone the repo
add the Zomato API key to zomatoApi.py file
open the terminal in the project directory and run the below commands
rasa train

Once the bot has been trained, run the bot using the below commands
rasa run actions

rasa run -m models --enable-api --cors "*" --debug
