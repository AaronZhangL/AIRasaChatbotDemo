# AIRasaChatbotDemo
A Chatbot demo base on RASA frame  
(Base on https://github.com/BSlience/rasa-conversational-ai)

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
