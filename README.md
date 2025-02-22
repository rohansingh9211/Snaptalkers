# Snaptalkers - Real-time Chat Application

**Snaptalkers** is a real-time chat application built with Django and Django Channels. This application allows users to engage in dynamic conversations with others in real time. It uses WebSockets to provide seamless messaging capabilities, ensuring a smooth, real-time experience.

## Features

- **Real-time Chat**: Users can send and receive messages instantly.
- **Channels**: Leverages Django Channels to support asynchronous operations.
- **WebSocket support**: Utilizes WebSockets for bidirectional communication.
- **User Authentication**: Users can sign up, log in, and start chatting immediately.
- **Message Notifications**: Real-time message notifications for connected users.
  
## Technologies Used

- **Django**: The web framework for building the application.
- **Django Channels**: Extends Django to handle WebSockets and asynchronous tasks.
- **ASGI**: Asynchronous server gateway interface for handling WebSocket connections.
- **Redis**: For managing WebSocket connections and handling message brokering.
- **SQLite**: Default database for user data storage (can be changed to PostgreSQL or MySQL).

## Installation

### 1. Clone the repository

git clone https://github.com/yourusername/snaptalkers.git
cd web_socket


The motive behind creating Snaptalkers, a real-time chat application, is to provide an intuitive, seamless, and dynamic messaging platform that allows users to interact and engage in live conversations.
