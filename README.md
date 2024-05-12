# Chat Application using Open API

This is a simple chat application built using Node.js, Express.js, Socket.io, and an open API for generating responses. Users can sign up, log in, set their online status, and engage in real-time messaging with other users.

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
     git clone https://github.com/your-username/chat-app.git
     ```
   - Install dependencies:
     ```
     cd chat-app
     npm install
     ```

2. **Configuration:**
   - Set up MongoDB and configure the connection string in `config.js`.
   - Obtain an API key for the language model API and update the code accordingly.

3. **Starting the Server:**
   - Run the server:
     ```
     npm start
     ```
   - The server will start at `http://localhost:3000`.

4. **Usage:**
   - Open the application in your browser.
   - Register a new account or log in with existing credentials.
   - Set your online status and start chatting with other users.

## Technologies Used

- Node.js
- Express.js
- Socket.io
- MongoDB
- JWT (JSON Web Tokens)
- Open API (e.g., ChatGPT, Claude, Gemini)

## Credits

- [Socket.io](https://socket.io/) for real-time communication.
- [Express.js](https://expressjs.com/) for building the server.
- [Mongoose](https://mongoosejs.com/) for MongoDB object modeling.
- [JWT](https://jwt.io/) for authentication.
- Open API providers for language model integration.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

