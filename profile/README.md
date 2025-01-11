# LinguaChat project

LinguaChat is a web application that enables users to communicate across different languages. It utilizes machine learning translation to translate bi-directionally in 1-on-1 chats in real time.

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
      - Provides modern easily customizable web components to speed up the development of the user interface
  -  Axios
      -  Speeds up the creation of HTTP requests and provides improved error handling
  -  Clerk
      - Complete authentication solution with frontend components and ready-built SDK for go backend server, and
      accessible webhooks for syncing data between Clerk and the project's own database

Backend:
  -  Go
      - High-performance language, offering efficient concurrency, and low latency that should work well for a real-time chat application  
  -  gin-gonic/gin
      - Lightweight go web framework for building the chat's RESTful backend API  
  -  gorilla/websocket
      - Websocket implementation for enabling real-time communication between users  

Translation API:
  - Pytorch
      - Machine learning framework for working with neural networks, used for additional training of pre-trained models and inference
  - Helsinki-NLP/opus-mt models
      - Models from HuggingFace that have good performance metrics. I tested BLEU scores for selected languages, and it seems to indicate that translation
        should be decent.
