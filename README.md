# 4461-P2-Chatbot

to create virtual env via condo(only need to do once):
```bash
conda create -n rasa_env python=3.9
```

to activate rasa environment:
```bash
conda activate rasa_env  
```

if you haven't installed rasa before(only need to do once):
```bash
pip3 install rasa
```

run this in a seperate terminal(also rasa env)(this is for running custom actions):
```bash
rasa run actions --port 5055
```

to train the rasa model:
```bash
rasa train
```
## After training, choose one of the following ways to run the bot:

1. in terminal:
```bash
rasa shell
```

2. to connect chatroom.js with the website:
```bash
python -m http.server
rasa run --enable-api --cors="*"
```
> you can then talk with the chatbot through the chatroom in index.html <br>
> Remember to keep the terminal running, or else the website won't work!

refer to [lab 1](https://github.com/Dingdong-LIU/Lab1_Chatbot_Rasa) for other command
