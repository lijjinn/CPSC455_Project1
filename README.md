#  User Guide:Real-Time Chat Application 

# Overview

Welcome to the Real-Time Chat Application! This web-based chat platform allows you to create or join chat rooms, send messages in real time, and interact with other users seamlessly.

# Features

- Instant messaging – Messages are sent and received in real time.

- Chat rooms – Users can join existing chat rooms using a room code or create their own.

- User-friendly interface – Simple and intuitive chat layout.

- Connection notifications – See when users join or leave a chat room.

- WebSocket communication: Messages are transmitted over a WebSocket connection using Flask-SocketIO.

- Secure and session-based – Users enter a name before joining a chat room.

- No rate limiting – Users can send messages without restrictions (see below for details).

# Technologies Used

- Flask (Python web framework)

- Flask-SocketIO (for WebSocket-based real-time communication)

- HTML, CSS, JavaScript (for the front-end UI)

- Socket.IO JavaScript Client (for real-time message updates)

# Installation

Ensure you have Python installed on your system.

Steps to Run Locally

1. Clone the repository:

`git clone https://github.com/lijjinn/CPSC455_Project1.git
cd CPSC455_Project1`

2. Install dependencies:

`pip install flask flask-socketio`

3. Run the server:

`python main.py`

# Getting Started

1. Open your browser
   
2. Navigate to: http://127.0.0.1:5000

# Joining a chat room

1. Click "Join a Room".
   
2. Enter the Room Code (provided by another user).
   
3. Click "Join" to enter the chat.

# Creating a Chat Room
After entering a name in the name bar
1. Click "Create a Room".
   
2. A unique Room Code will be generated once entered into chat room.
   
3. Share this code with friends so they can join.
   
4. Start chatting in real time!

# Sending Messages 

- Type your message in the input box at the bottom.
- Click "Send" to send your message.
- Messages appear instantly in the chat window.

# Rate Limiting (Not Implemented)

This chat application does not include rate limiting. Attempts were made to add a spam prevention system, but the prevention system caused a glitch where valid messages such as just regular messages were detected as spam mistakenly, preventing users from sending messages properly or at all. Due to this issue, rate limiting was not included in this program to ensure smooth messaging.

As a result, users can currently send messages as fast as they like. 

# Messages Are Not Sending
- Ensure you have a stable internet connection.
- Try refreshing the page.

# License

This project is licensed under the MIT License.
