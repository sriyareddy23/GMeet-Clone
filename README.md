# GMeet-Clone

## Project Overview

The GMeet-Clone project is a replica of Google Meet, providing real-time video conferencing, chat functionality, screen sharing, and file-sharing capabilities. Developed using WebRTC, this project enables seamless remote collaboration by mimicking the core features of Google Meet.

## Project Team

- [@SatyamJais10](https://github.com/SatyamJais10)
- [@sriyareddy23](https://github.com/sriyareddy23)

## Features

- **Video Conferencing**: Users can organize meetings where others can join using a unique meeting ID.
- **Chatbox**: Real-time messaging is supported, allowing users to chat with others in the meeting.
- **Screen Sharing**: Participants can share their screens with others in the meeting for better collaboration.
- **File Sharing**: Users can upload and share attachments within the meeting.

## Prerequisites

- **Node.js**: Ensure that Node.js is installed on your machine to run the server.

## Technology Stack

- **Socket.io**: A popular JavaScript library used to facilitate real-time bi-directional communication between the browser and server.
- **WebRTC**: Technology enabling real-time communication for video conferencing and screen sharing.
- **HTML, CSS, JavaScript**: For the frontend user interface and interaction.
- **Passport.js**: Used for Google authentication to secure user access.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/gmeet-clone.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd gmeet-clone
    ```

3. **Install Dependencies**:
    ```bash
    npm install
    ```

4. **Start the Server**:
    ```bash
    npm start
    ```

5. **Access the Application**:
    - Open your browser and navigate to `http://localhost:3000` to start using the GMeet clone.

## How It Works

- **User Connections**: When a user connects, their information is tracked, and the server informs other participants about the new connection.
- **Messaging**: Messages sent by users in the chatbox are broadcast to all participants in the meeting.
- **File Sharing**: Users can upload files that are shared with other participants in the meeting.
- **Screen Sharing**: The app allows users to share their screens in real-time during a meeting.

## Conclusion

The GMeet-Clone is an excellent example of how real-time communication technologies like WebRTC and Socket.io can be used to build robust video conferencing tools. It provides essential features required for effective remote collaboration, making it a valuable project for learning and development.
