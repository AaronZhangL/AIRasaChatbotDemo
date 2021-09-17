# AIRasaChatbotDemo
A Chatbot demo base on RASA frame  

## Init Rasa

```bash
rasa init
```

## Build Rasa

```bash
rasa train nlu
rasa test nlu

rasa data validate stories
rasa train core
rasa test core
rasa train

```
