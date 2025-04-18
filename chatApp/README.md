# chatApp

This app will be used as a chat app, something similar to whatsapp. With features to make a group chat. To see when messages is delivered/seen. Send text messages and also files.

Techstack:

Backend (NestJS):

- REST API (for auth, user, chat management)
- WebSocket Gateway (for real-time messaging)
- JWT-based authentication
- TypeORM (MongoDB)

Frontend (Angular):

- Login/Register
- Chat list
- Real-time chat window (using @angular/websocket)
- Auth guards + state management (RxJS)
