### User Guide: Real-Time Chat Application

Overview: 

Welcome to the Real-Time Chat Application! This web-based chat platform allows you to create or join chat rooms, send messages in real time, and interact with other users seamlessly.


Features
- **Instant messaging** – Messages are sent and received in real time.
- **Chat rooms** – Users can join existing chat rooms using a room code or create their own.
- **User-friendly interface** – Simple and intuitive chat layout.
- **Connection notifications** – See when users join or leave a chat room.
- **WebSocket communication** – Messages are transmitted over a WebSocket connection using Flask-SocketIO.
- **Secure and session-based** – Users enter a name before joining a chat room.
- **Rate limiting** – Users can send up to 5 messages within 10 seconds to prevent spam.

Technologies Used
- **Flask** (Python web framework)
- **Flask-SocketIO** (for WebSocket-based real-time communication)
- **HTML, CSS, JavaScript** (for the front-end UI)
- **Socket.IO JavaScript Client** (for real-time message updates)

Installation
Ensure you have Python installed on your system.

### Steps to Run Locally
1. **Clone the repository:**
   ```bash
   git clone https://github.com/lijjinn/CPSC455_Project1.git
   cd CPSC455_Project1
   ```
2. **Install dependencies:**
   ```bash
   pip install flask flask-socketio
   ```
3. **Run the server:**
   ```bash
   python main.py
   ```

Getting Started
- **Open your browser**
- **Navigate to:**  
  - HTTP: `http://127.0.0.1:5000`  
  - WebSocket: `ws://127.0.0.1:5000`

### Joining a Chat Room
1. Click **"Join a Room"**.
2. Enter the **Room Code** (provided by another user).
3. Click **"Join"** to enter the chat.

### Creating a Chat Room
1. Enter your **name** in the input field.
2. Click **"Create a Room"**.
3. A **unique Room Code** will be generated.
4. Share this code with friends so they can join.
5. Start chatting in real time!

### Sending Messages
1. Type your message in the input box at the bottom.
2. Click **"Send"** to send your message.
3. Messages appear instantly in the chat window.

### Rate Limiting 
To prevent spam, **each user can send a maximum of 5 messages within 10 seconds**. If the limit is exceeded, a message will appear stating:
```
Rate limit exceeded. Please wait a moment.
```
This ensures smooth messaging while preventing excessive spam.

### Troubleshooting
#### Messages Are Not Sending
- Ensure you have a **stable internet connection**.
- Try **refreshing the page**.
- Check if you've hit the **rate limit** and wait a few seconds.

### License
This project is licensed under the **MIT License**.

* *used AI for formatting user guide* *
