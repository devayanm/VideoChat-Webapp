# VideoChat-Webapp

This is a simple video chat web application that allows users to have real-time video conversations. The app is built using EJS, Socket.io, WebRTC, PeerJS, Node.js, Express, HTML, CSS, and JavaScript.

## Features

- Real-time video chat functionality
- Unique room generation using UUID
- Easy-to-use interface
- Scalable and modular codebase
- Cross-browser compatibility

## Prerequisites

- Node.js and npm installed on your machine

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/devayanmm/VideoChat-Webapp.git
   ```

2. Navigate to the project directory:
   ```bash
   cd video-chat-app
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

## Usage

1. Start the server:
   ```bash
   npm start
   ```

2. Open your web browser and navigate to `http://localhost:3000`.

3. Enter your name and the desired room name, then click "Join Room."

4. Share the generated room URL with your friend and ask them to join using the same room name.

5. Enjoy your real-time video chat!

## Technologies Used

- EJS: Embedded JavaScript templating for generating dynamic HTML content.
- Socket.io: Real-time communication library for enabling instant messaging.
- WebRTC: Web Real-Time Communication API for peer-to-peer audio and video communication.
- PeerJS: Simplified WebRTC wrapper for easier handling of peer connections.
- Node.js: JavaScript runtime for server-side development.
- Express: Web application framework for building robust APIs and web apps.
- HTML: Hypertext Markup Language for structuring the web page.
- CSS: Cascading Style Sheets for styling the web page.
- JavaScript: Programming language for adding interactivity to the web page.

## Project Structure

```
.
├── public
│   ├── css
│   │   └── style.css
│   ├── js
│   │   └── script.js
├── views
│   ├── room.ejs
├── .gitignore
├── package.json
├── server.js
└── README.md
```

## Contributions

Contributions are welcome! Feel free to open issues and submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README according to your project's specifics. Make sure to update the installation and usage instructions, project structure, and any additional features you might add. Good luck with your Video Chat Web App!