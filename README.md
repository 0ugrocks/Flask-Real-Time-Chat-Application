# Real-Time Chat Application

This project is a **real-time chat application** built using **Flask** and **Socket.IO** for the backend, and **HTML**, **CSS**, and **jQuery** for the frontend. The application allows multiple users to communicate instantly in a chat room environment.

## Features
- **Real-Time Messaging:** Users can send and receive messages instantly without refreshing the page.
- **User Management:** Simple username system to identify users in the chat room.
- **Responsive Frontend:** The interface is clean and responsive, built with HTML, CSS, and enhanced with jQuery for dynamic interactions.
- **Socket.IO Integration:** Utilizes WebSockets via Flask-SocketIO for seamless bidirectional communication between clients and server.

## Backend
- **Flask:** Provides a lightweight framework to handle HTTP requests and manage routing.
- **Flask-SocketIO:** Handles WebSocket connections to enable real-time communication.
- **Event Handling:** Implements events for joining, leaving, and sending messages in the chat room.

## Frontend
- **HTML & CSS:** Structured and styled the chat interface for a clean user experience.
- **jQuery:** Handles dynamic updates and interactions without full page reloads.
- **Real-Time Updates:** Listens to Socket.IO events to instantly display new messages.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/realtime-chat-app.git
