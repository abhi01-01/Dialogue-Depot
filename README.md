
# Dialogue-Depot

Dialogue-Depot is a Full Stack Chatting App.
Uses Socket.io for real time communication and stores user details in encrypted format in Mongo DB Database.
## Tech Stack

**Client:** React JS

**Server:** Node JS, Express JS

**Database:** Mongo DB
  
## Demo

Go to the project directory

```bash
  cd mern-chat-app
```

Install dependencies

```bash
  npm install
```

```bash
  cd frontend/
  npm install
```

Start the server

```bash
  npm run start
```
Start the Client

```bash
  //open now terminal
  cd frontend
  npm start
```

## API Endpoints

- **POST /api/user/signup**: User registration.
- **POST /api/user/login**: User login.
- **GET /api/user/search**: Search for users.
- **POST /api/chat**: Create a new chat.
- **GET /api/chat**: Fetch user chats.
- **POST /api/chat/group**: Create a group chat.
- **PUT /api/chat/rename**: Rename a group chat.
- **PUT /api/chat/groupremove**: Remove a user from a group.
- **PUT /api/chat/groupadd**: Add a user to a group.
- ... (and more)




  
