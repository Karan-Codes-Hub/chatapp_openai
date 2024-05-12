# Chat Application using Open API

This is a simple chat application built using Node.js, Express.js and an open API for generating responses. Users can sign up, log in, set their online status, and engage in real-time messaging with other users.

## Features

1. **User Authentication:**
   - Users can register with an email and password.
   - JWT (JSON Web Tokens) are used for authentication.

2. **Chat Functionality:**
   - Real-time messaging using Socket.io for efficient communication.
   - Users can send and receive messages instantly.

3. **Message Storage:**
   - All chat messages are stored in MongoDB.
   - Messages are retrievable for conversation history.

4. **User Online Status:**
   - Users can set their status as 'AVAILABLE' or 'BUSY'.
   - Online status is updated in real-time.

5. **Language Model API Integration:**
   - When a user tries to chat with someone who is 'BUSY', an appropriate response is generated using an open API such as ChatGPT, Claude, Gemini, etc.
   - The API response is sent within 10 seconds, or a standard message indicating user unavailability is sent.

## Usage

1. **Installation:**
   - Clone the repository:
     ```
     git clone https://github.com/your-username/chatapp_openai.git
     ```
   - Install dependencies:
     ```
     cd chatapp_openai
     
     ```
     Now Run npm install and npm run dev on both server and client
     ```
     npm install
     npm run dev
     ```.

2. **Usage:**
   - Open the application in your browser.
   - Register a new account or log in with existing credentials.
   - Set your online status and start chatting with other users.

## Technologies Used

- Node.js
- Express.js
- ChatEngine
- JWT (JSON Web Tokens)
- Open API (e.g., ChatGPT, Claude, Gemini)

## Credits
- [Express.js](https://expressjs.com/) for building the server.
- [JWT](https://jwt.io/) for authentication.
- Open API providers for language model integration.



