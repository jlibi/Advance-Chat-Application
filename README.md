# Group Chatting Application

This is a simple group chatting application built using Java and Java Swing. The application allows multiple users to connect to a server and participate in a group chat.

## Features

- User authentication (username and password)
- Send and receive text messages in a group chat
- Display user information and group details
- Real-time message broadcasting to all connected clients

## Prerequisites

- Java Development Kit (JDK) installed on your system

## Getting Started

1. Clone the repository or download the source code.
2. Open the project in your preferred Java IDE.
3. Compile and run the `Server.java` file to start the server.
4. Compile and run the `UserOne.java` and `UserTwo.java` files to launch the client applications.

## Usage

- When launching a client application (`UserOne` or `UserTwo`), you will be prompted to enter your username and password.
- Upon successful authentication, the client application will connect to the server, and you can start sending and receiving messages in the group chat.
- Type your message in the text field at the bottom and click the "Send" button or press Enter to send the message.
- Received messages from other users will be displayed in the chat area.
- Click on the group name to view the group information and user details.

## Code Structure

- `Server.java`: Handles the server-side logic for accepting client connections and broadcasting messages.
- `UserOne.java` and `UserTwo.java`: Represent two different client applications with separate user interfaces.
- `UserAuthentication.java`: Contains a simple implementation of user authentication based on hardcoded credentials.
- `InformationPanel.java`: Displays group information and user details.
