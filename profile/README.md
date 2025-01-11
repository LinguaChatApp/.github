# LinguaChat project
1 on 1 chats with translated messages

[Frontend Repository](https://github.com/LinguaChatApp/linguachat-frontend)

[Backend Repository](https://github.com/LinguaChatApp/linguachat-backend-go)

[Translation API Repository](https://github.com/LinguaChatApp/linguachat-translation-api)


## Tech Stack
Technologies used, and reason for using them.

Frontend:
  - TypeScript
      - Strongly typed, better code interpretability and maintainability, better error detection,
        and better development experience than using javascript
  -  React
      -  Component-based library that is ideal for creating the dynamic user interface for this chat application, plus I have previous experience
  -  Mantine UI
      - Provides modern easily customizable web components to speed up development of user interface
  -  Axios
      -  Speeds up creation of http requests and provides improved error handling
  -  Clerk
      - Complete authentication solution with frontend components and ready-built sdks for backend server, and
      accessible webhooks for syncing of data between Clerk and project's database

Backend:
  -  Go
      - High performance language, offering efficient concurrency, and low latency that should work well for a real-time chat application  
  -  gin-gonic/gin
      - Lightweight go web framework for building the chat's RESTful backend API  
  -  gorilla/websocket
      - Websocket implementation for enabling real-time communication between user's  

Translation API:
  - Pytorch
      - Machine learning framework for working with neural networks, used for additional training of pretrained models and inference
  - Helsinki-NLP/opus-mt models
      - Models from HuggingFace that have good performance metrics, personally tested BLEU scores for selected languages seem to indicate that translation
        should be decent
