# Realtime Chat App with MERN stack (Frontend)

### Introduction
This repo consists of the **Frontend** part of a Realtime Chat Application built with the MERN stack. I built it when I was trying to learn React and the stack for the first time.
You can find the backend repo [here](https://github.com/kunaldeshwal1/Chatapp-server).

### Feature
- Create a room and start a **Room Chat** for users who want to broadcast messages to a specific group of users.
- Real-time updates to conversation messages.

### Technologies
- database - MongoDB
- backend - Express.js & Node.js
- frontend - React.js (with styled-components)
- Real-time messages - Socket.io

### Deploy
- database: MongoDB Atlas

### How to use
1. Clone the repo
    ```
    git clone https://github.com/kunaldeshwal1/Chatapp-client.git
    ```
2. Enter the directory
    ```
    cd Chatapp-client
    ```
3. Install dependencies
    ```
    yarn install
    ```
4. Change .env.example file
   - change file name to .env
   - go to https://multiavatar.com to create an account and get your avatar api key
   - change the VITE_SERVER_URL to your local server port (ex. http://localhost:5000 for server listening to port 5000)

5. Run the app   
    -> Please make sure the server for this app is running before running the client, to setup for the server.
    ```
    yarn dev
    ```
    The app will be automatically opened in your web browser and you can try it out.
