PROJECT TITLE

Chat Application with Socket.IO

PROJECT DESCRIPTION

This is a chat application built with Socket.IO and React that allows users to join chat rooms and send messages in real-time.

USAGE

To run the application, first clone the repository from GitHub:

$ git clone https://github.com/your-username/chat-app.git

Then, navigate to the project directory and install the dependencies:

$ cd chat-app
$ npm install

To start the server and the client, run:

$ npm run dev

This will start the server on port 3001 and the client on port 3000.

Once the server and client are running, open your web browser and go to http://localhost:3000 to use the application.

YOUTUBE CHANNEL

Check out my YouTube channel Coding Circulate for more tutorials and projects like this one!

FRONTEND

The frontend of this application was built with React and Socket.IO client. The main components of the frontend are:

- `App.js`: The main component that renders the `Join` component and the `Chat` component based on the user's authentication status.
- `Join.js`: The component that allows the user to enter their name and the name of the chat room they want to join.
- `Chat.js`: The component that displays the chat room and the messages. It allows the user to send messages and displays messages sent by other users in real-time.

BACKEND

The backend of this application was built with Node.js, Express, Socket.IO, and cors. The main components of the backend are:

- `index.js`: The main file that sets up the server and the Socket.IO connection.
- `socket.js`: The file that contains the Socket.IO logic for handling events such as `join_room` and `send_message`.
- `cors`: A middleware that allows cross-origin resource sharing between the client and the server.

Thanks for checking out this project! If you have any questions or suggestions, feel free to reach out to me on GitHub or my YouTube channel.
