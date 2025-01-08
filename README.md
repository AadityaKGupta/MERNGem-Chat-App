# MERNGem Chat App

A real-time, AI-powered chat application built using the MERN stack (MongoDB, Express, React, Node.js), enhanced with Google Gemini for AI-powered features, Redis for performance optimization, and Socket.io for seamless real-time communication.

## Features

- **Real-time Messaging**: Instant communication with WebSocket/Socket.io.
- **AI Integration**: Leverages Google Gemini for intelligent chat responses and enhanced user interactions.
- **Redis Optimization**: Improves performance with caching and real-time data handling.
- **User Authentication**: Secure sign-in via Google OAuth integration.
- **Scalable Architecture**: Built on the MERN stack for a robust and scalable application.

## Technologies Used

- **Frontend**: React.js, Socket.io (for real-time communication)
- **Backend**: Node.js, Express.js, Socket.io
- **Database**: MongoDB
- **Authentication**: Google Gemini (OAuth2)
- **Performance**: Redis (for caching and optimization)

## Installation

### Prerequisites

- Node.js (v12 or above)
- MongoDB
- Redis (for caching, optional but recommended)

### Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/MERNGem-Chat-App.git
   cd MERNGem-Chat-App
   ```

2. Install dependencies for both backend and frontend:
   - **Backend**:
     ```bash
     cd backend
     npm install
     ```
   - **Frontend**:
     ```bash
     cd frontend
     npm install
     ```

3. Set up environment variables:
   Create a `.env` file in the backend folder with the following values:
   ```plaintext
   GOOGLE_CLIENT_ID=your-google-client-id
   GOOGLE_CLIENT_SECRET=your-google-client-secret
   REDIS_URL=your-redis-url (if using Redis)
   ```

4. Start the application:
   - **Backend**:
     ```bash
     cd backend
     npm start
     ```
   - **Frontend**:
     ```bash
     cd frontend
     npm start
     ```

5. Open the app in your browser at `http://localhost:3000`.

## Usage

- **User Authentication**: Sign in with your Google account.
- **Real-time Chat**: Start messaging in the chat interface.
- **AI Assistance**: Receive intelligent suggestions and responses powered by Google Gemini.

## Contributing

Feel free to fork the repository and submit issues or pull requests for improvements. Contributions are welcome!

## License

This project is licensed under the MIT License.
