# RestaurantChatBot
 Restaurant Chat Bot built using Zomato API and RASA Framework
Prerequisites
1. Zomato API Key
2. Rasa Framework

How to use

1.Clone the repo

2.add the Zomato API key to zomatoApi.py file

3.open the terminal in the project directory and run the below commands

  rasa train
  

4.Once the bot has been trained, run the bot using the below commands

  rasa run actions
  
  rasa run -m models --enable-api --cors "*" --debug
  
