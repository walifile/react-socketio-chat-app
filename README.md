# Chat Application with Socket.IO

This is a chat application built with Socket.IO and React that allows users to join chat rooms and send messages in real-time.

## Features

- Create and join chat rooms
- Send and receive messages in real-time

## Technologies Used

- React
- Node.js
- Express
- Socket.io

## Usage

1. Clone the repository: `git clone https://github.com/walifile/react-socketio-chat-app.git`
2. Install dependencies: `npm install`
3. Start the server: `npm run server`
4. Start the client: `npm start`
5. Navigate to `http://localhost:3000` in your web browser

## FRONTEND

The frontend of this application was built with React and Socket.IO client. The main components of the frontend are:

- `App.js`: The main component that renders the `Join` component and the `Chat` component based on the user's authentication status.
- `Join.js`: The component that allows the user to enter their name and the name of the chat room they want to join.
- `Chat.js`: The component that displays the chat room and the messages. It allows the user to send messages and displays messages sent by other users in real-time.

## BACKEND

The backend of this application was built with Node.js, Express, Socket.IO, and cors. The main components of the backend are:

- `index.js`: The main file that sets up the server and the Socket.IO connection.
- `socket.js`: The file that contains the Socket.IO logic for handling events such as `join_room` and `send_message`.
- `cors`: A middleware that allows cross-origin resource sharing between the client and the server.

## Support

If you found this project helpful and want to support me, you can buy me a coffee at:

[![Buy me a coffee](https://img.shields.io/badge/-Buy%20me%20a%20coffee-orange?logo=buy-me-a-coffee&logoColor=white&labelColor=orange&color=white)](https://www.buymeacoffee.com/waliahmad9)

## My YouTube Channel

Check out my YouTube channel, Coding Circulate, for more web development content: [Coding Circulate](https://www.youtube.com/@codingcirculate/featured)

Thanks for checking out this project! If you have any questions or suggestions, feel free to reach out to me on GitHub or my YouTube channel.
