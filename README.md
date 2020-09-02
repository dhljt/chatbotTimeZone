# chatbotTimeZone
Little chatbot creadted with Rasa and Python to get the Time Zone of any city

Basically you can start like this in your CMD

rasa init    # where it will ask you a path for your new bot

All you have to do is, config your chatbot by coding and changing your files:

  nlu.md,
  stories.md,
  domain.yml,
  endpoints.yml,
  actions.py
  
 then anytime you want to try your new changes:
 
 rasa shell       # to start your chatbot
 
 rasa shell nlu   # to show your match with your text
 
 rasa run actions # to start the server for your actions
 
