# Chat Application

This is a simple chat application built using HTML, JavaScript, and Node.js. It allows users to chat in real-time with each other in a web-based environment. The application uses various libraries and modules to enable its functionality.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Real-time chat functionality.
- User authentication with usernames.
- Send and receive messages instantly.
- Minimalist and user-friendly interface.

## Technologies Used

- **HTML**: The front-end structure of the application is built using HTML for rendering web content.

- **JavaScript**: The core logic and interactivity of the application are implemented using JavaScript.

- **Node.js**: The server-side of the application is built on Node.js, which allows for handling multiple concurrent connections and real-time messaging.

- **Express.js**: The web framework used to build the server and handle HTTP requests.

- **Socket.io**: A library for enabling real-time, bidirectional communication between clients and server.

- **Passport.js**: Used for user authentication and session management.

- **SQLite**: A lightweight, file-based database for storing user information and chat messages.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm are installed on your machine. You can download them from [nodejs.org](https://nodejs.org/).

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/chat-application.git
   ```

2. Navigate to the project directory:

   ```bash
   cd chat-application
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the project root directory and set the following environment variables:

   ```
   SESSION_SECRET=your-session-secret
   ```

   Replace `your-session-secret` with a secure secret for session management.

5. Initialize the SQLite database:

   ```bash
   node initDB.js
   ```

## Usage

1. Start the application:

   ```bash
   npm start
   ```

   The server will start on `http://localhost:3000`.

2. Open your web browser and navigate to `http://localhost:3000` to access the chat application.

3. Sign up for an account or log in with an existing one.

4. Start chatting with other users in real-time.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository on GitHub.

2. Clone your forked repository to your local machine.

3. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name`.

4. Make your changes and commit them with a descriptive commit message.

5. Push your changes to your forked repository on GitHub.

6. Create a pull request to merge your changes into the main repository.

Please ensure your code follows the project's coding guidelines and includes appropriate tests if applicable.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
