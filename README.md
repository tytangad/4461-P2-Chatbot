# 4461-P2-Chatbot

to create virtual env via condo:
```bash
conda create -n rasa_env python=3.9
```

to activate rasa environment:
```bash
conda activate rasa_env  
```
if you haven't installed rasa before
```bash
pip3 install rasa
```

to train the rasa model:
```bash
rasa train
```

to run the rasa chatbot:
```bash
rasa shell
```

to connect chatroom.js with the website:
```bash
python -m http.server
rasa run --enable-api --cors="*"
```
