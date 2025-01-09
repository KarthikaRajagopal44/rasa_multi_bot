# Rasa chatbot example
This is an example bilingual rasa chatbot implementation that can be connected to your Facebook page using chatfuel.

Chatfuel comes with a bunch of features one of which is providing a messenger channel to receive messages from facebook along with other attributes including what we need, user’s profile language. It also gives you a nice get started button so you can provide a nice welcome message for the user. Chatfuel also provides a backend integration webhook namely JSON API to pass the user message to the Rasa servers that i am running in my backend. Goal is to interpret the message from Chatfuel and provide a response back

## Proof of Concept
The project is a quick implementation to demonstrate a desired architecture of Rasa components using the latest tensforflow embeddings
in French and English


## How to start

Requirements 
- Docker

### 1
```
docker-compose up --build

```

### 2
You will have two servers up 
at localhost:5005 - serving the english model
at localhost:5006 - serviing the french model

### 3
Redis tracker is running at port 6379
