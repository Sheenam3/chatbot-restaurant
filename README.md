# chatbot-restaurant

Simple chatbot for restaurant customers asking for menu.
You can enhance it further based on your requirements and understanding


# Try it
1. Install anaconda on your machine by following the steps here:

    For ubuntu 18.04
    https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart

2. <b>Clone this rasa project</b>
 <code>git clone 'github path'</code>
  After cloning, enter into chatbot-restaurant directory. 
```
├── actions.py
├── config.yml
├── credentials.yml
├── data
│   ├── nlu.md
│   └── stories.md
├── domain.yml
├── endpoints.yml
├── events.db
├── events.db-shm
├── events.db-wal
├── __init__.py
├── models
│   ├── 20201014-015342.tar.gz
│   └── 20201014-020640.tar.gz
├── __pycache__
│   ├── actions.cpython-36.pyc
│   └── __init__.cpython-36.pyc
├── rasa.db
└── tests
    └── conversation_tests.md
```

 # Train the model:
  If you have made any changes to the project, then train it first.
  
  `rasa train`
  
# Install <b>rasa x</b>
  Rasa X is a tool for Conversation-Driven Development (CDD), the process of listening to your users and using those insights to improve your AI assistant.

  On Local Mode:
  <code>pip3 install rasa-x --extra-index-url https://pypi.rasa.com/simple</code>

  `rasa x`
  
  This will open up rasa x webpage on your browser, where you can interact with your bot and test it.
  


# Screenshots

Conversation with the bot: 

![alt text](https://github.com/Sheenam3/chatbot-restaurant/blob/master/screenshots/bot1.png "Bot 1")


![alt text](https://github.com/Sheenam3/chatbot-restaurant/blob/master/screenshots/bot2.png "Bot 1")




