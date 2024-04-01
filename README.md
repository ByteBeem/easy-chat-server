# easy-chat-server

easy-chat-server is a Node.js module for quickly setting up a real-time chat server using Socket.IO.

## Features

- Simple setup: Easily create a real-time chat server with just a few lines of code.
- Real-time messaging: Instantly send and receive messages between connected clients.
- Customizable: Customize the chat server to fit your specific requirements.
- Scalable: Scale your chat server to handle any number of users.

## Installation

To install easy-chat-server, use npm or yarn:

```bash
npm install easy-chat-server

or

yarn add easy-chat-server

```
# Usage

Here's how you can set up a basic chat server using easy-chat-server:

const express = require('express');
const http = require('http');
const initializeChatServer = require('easy-chat-server');

const app = express();
const server = http.createServer(app);

// Initialize chat server
initializeChatServer(server);

const PORT = process.env.PORT || 3000;
server.listen(PORT, () => {
    console.log(`Server is running on port ${PORT}`);
});


# Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug fixes, please open an issue or submit a pull request.
