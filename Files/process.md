# RASA chatbot
## Installing RASA
First, install rasa in you computer. It can be done into a virtual environment.
```
pip3 install rasa
```
This process should take some minutes to complete.

## Generating a Simple chatbot
To create a simple rasa bot, enter the following lines into  a terminal:
```
rasa init
```
Follow the instructions and train the model.

## Special commands
There are some special useful commands that are needed:
* **rasa shell** this command initialize the chatbot, just open the chatbot directory and run in terminal
* **rasa shell nlu** this command initialize the NLU (Natural Language Unit) to identify the intents related
* **rasa train** Use this command to train the model
* **rasa run actions** this command initialize the webhook.
