# Covid-19-ChatBot
The chat bot answers various questions related to COVID-19 outbreak in India using Natural Language Understanding. Such as the latest news, the number of cases in any particular state, nearest hospitals. The back end is in python which hits the official India covid-19 URL for data retrieval based on user response. The front is in JavaScript and communication is through through REST API's.

# To Train Chat Bot
Open Rasa folder in Command Prompt
 -> python -m rasa train
 
# To run action server
Open Rasa folder in Command Prompt
-> python -m rasa run actions

# To run nlu server
Open Rasa folder in Command Prompt
-> python -m rasa run -m models --enable-api --cors "*" --debug

# To chat with bot
Open Rasa folder in Command Prompt
-> python -m rasa shell
