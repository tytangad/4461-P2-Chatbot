# 4461-P2-Chatbot

to activate rasa environment:
```bash
conda activate rasa_env  
```

to train the rasa model:
```bash
rasa train
```

to run the rasa chatbot:
```bash
rasa shell
```

to connect the chatbot with the website:
```bash
python -m http.server
rasa run --enable-api --cors="*"
```
