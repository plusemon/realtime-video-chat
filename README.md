# Real-time Video Chat Application

This is a simple real-time video chat application that allows users to connect with each other using their webcams and microphones.

## Features

*   **User Authentication:** Users can create a username to join the chat.
*   **Contact List:** See a list of all online users.
*   **WebRTC Video/Audio:** Engage in one-on-one video calls.
*   **Real-time Communication:** Socket.io enables instant messaging and call signaling.

## Technologies Used

*   **Frontend:** HTML, CSS, JavaScript
*   **Backend:** Node.js, Express.js
*   **Real-time Communication:** Socket.io
*   **Peer-to-Peer Connection:** WebRTC

## Getting Started

### Prerequisites

*   Node.js and npm installed on your machine.

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/realtime-video-chat.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd realtime-video-chat
    ```
3.  Install the dependencies:
    ```bash
    npm install
    ```

### Running the Application

1.  Start the server:
    ```bash
    npm start
    ```
2.  Open your browser and navigate to `http://localhost:3000`.

## How to Use

1.  Enter a username and click "Create".
2.  You will see a list of online users.
3.  Click the "Call" button next to a user's name to initiate a video call.
4.  The other user will receive an incoming call notification.
5.  Once the call is accepted, you will be connected in a video chat.
6.  To end the call, click the "End Call" button.
