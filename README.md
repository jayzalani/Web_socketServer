## WebSocket Introduction

WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. It's designed to be implemented in web browsers and web servers, but can be used by any client or server application.

The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011. It provides a way for a server and client to open a TCP connection and then exchange data in any format they choose, with no limit on the amount of data that can be sent. The WebSocket protocol is an independent TCP-based protocol, which means that it can be implemented and used on top of existing HTTP infrastructure.

The main features of WebSocket are:

1. **Full-duplex communication**: WebSocket enables bidirectional communication between the client and server, allowing both parties to send data at any time.
2. **Low latency**: WebSocket provides a low-latency communication channel, as it eliminates the overhead of repeated HTTP headers and the request-response cycling.
3. **Persistent connection**: WebSocket maintains a persistent connection between the client and server, reducing the need for repeated handshakes and authentication.
4. **Real-time data exchange**: WebSocket is suitable for applications that require real-time data exchange, such as chat applications, online games, and real-time monitoring systems.

## Overview

This is a real-time chat application built using WebSocket technology. It allows users to connect, send messages, and see other users' messages in real-time.

## Features

- Real-time messaging
- User presence indicators
- Typing indicators
- Message history
- User authentication

## Technologies Used

- **Server-side**: Node.js, Socket.IO
- **Client-side**: React.js, Socket.IO client
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)

## Getting Started

1. Clone the repository:
```
git clone https://github.com/your-username/websocket-chat-app.git
```
2. Install dependencies:
```
cd websocket-chat-app
npm install
```
3. Start the server:
```
npm start
```
4. Open your web browser and navigate to `http://localhost:3000` to access the application.

## Usage

1. Sign up or log in to the application.
2. Start chatting with other users in real-time.
3. See which users are currently online.
4. View the message history.

## Contributing

If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and ensure that the code passes all tests.
4. Commit your changes and push your branch to your forked repository.
5. Submit a pull request to the original repository.

## License

This project is licensed under the [MIT License](LICENSE).
