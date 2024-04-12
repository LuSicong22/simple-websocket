

# WebSocket Example with Node.js and JavaScript

This repository contains a simple example demonstrating how to implement WebSocket communication using Node.js on the server-side and JavaScript on the client-side. WebSockets enable real-time bidirectional communication between clients and servers, making them ideal for applications that require instant updates and interactions.
**Link of relevant technical blog:**
https://mirror.xyz/0x6a0A7dcAdbDd4862c9A7637119e379EC04ddFeec/b0-tGjCccuYas64zaJ9K0zq4giQTgmChDj680XxnPqo
## Getting Started

To run the example code, follow these steps:

### Prerequisites

- Node.js installed on your machine.

### Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/LuSicong22/simple-websocket.git
```

2. Navigate to the project directory:

```bash
cd simple-websocket
```

3. Install the required dependencies:

```bash
npm install
```

### Usage

1. Start the WebSocket server:

```bash
node server.js
```

The server will start listening for WebSocket connections on port `8080`.

2. Open the `index.html` file in a web browser.

3. Enter a message in the input field and click the "Send Message" button.

4. Check the browser console to see the message being sent to the server and the response received from the server.

### Example Explanation

- The `server.js` file contains the server-side code written in Node.js. It creates a WebSocket server using the `ws` library and listens for incoming connections on port `8080`. Upon receiving a message from a client, it echoes the message back to the client.

- The `index.html` file contains the client-side code written in HTML and JavaScript. It establishes a WebSocket connection with the server and sends a message to the server when the user clicks the "Send Message" button. It also listens for messages from the server and logs them to the browser console.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README to fit your project's specific needs. If you have any questions or encounter any issues, please don't hesitate to reach out!
