# Real-Time Chat Application 

# Overview

This project is a real-time chat application built using Flask and Socket.IO. It allows users to join or create chat rooms, send and receive messages in real time, and manage multiple active users per room.

# Features

- Real-time messaging: Users can send and receive messages instantly.

- Room-based chat: Users can create or join chat rooms using unique room codes.

- User authentication (session-based): Users must enter a name before joining a chat room.

- WebSocket communication: Messages are transmitted over a WebSocket connection using Flask-SocketIO.

- Automatic room management: The system automatically deletes inactive rooms.

- Graceful handling of connections and disconnections: Users joining or leaving rooms trigger notifications.

# Technologies Used

- Flask (Python web framework)

- Flask-SocketIO (for WebSocket-based real-time communication)

- HTML, CSS, JavaScript (for the front-end UI)

- Socket.IO JavaScript Client (for real-time message updates)

# Installation


Ensure you have Python 3.x installed on your system.

Steps to Run Locally

1. Clone the repository:

`git clone https://github.com/lijjinn/CPSC455_Project1.git
cd CPSC455_Project1`

2. Install dependencies:

`pip install flask flask-socketio`

3. Run the server:

`python main.py`

# Access the application:
Open your browser and navigate to:

http://127.0.0.1:5000

# Usage Instructions

Open the application in your browser.

- Enter a name and either:

- Join an existing room using a room code.

- Create a new chat room, which generates a unique room code.

- Once inside a chat room:

- Send messages in real time.

- See messages from other participants.

- Users joining or leaving are notified.

# License

This project is licensed under the MIT License.
