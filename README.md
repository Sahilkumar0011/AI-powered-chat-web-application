# Collaborative Chat and AI-Powered Assistant - MERN Stack

A full-stack web application built with the MERN (MongoDB, Express.js, React.js, Node.js) stack. This app allows users to:

- Create and manage multiple projects.
- Add collaborators to projects and chat with them in real-time.
- Chat with an AI assistant by typing `@ai` followed by a message, to receive AI-generated responses.
- Supports user authentication using JWT and chat functionality through WebSockets.

## Features

- **User Authentication**: Register and log in to access project and collaboration features.
- **Create and Manage Projects**: Add new projects, edit existing ones, and delete them.
- **Collaborator Management**: Invite collaborators to join projects and collaborate in real-time chat.
- **Real-Time Chat**: Chat with collaborators and AI using WebSockets for real-time communication.
- **AI Integration**: Type `@ai` followed by a message to chat with the AI agent, powered by Gemini API.
- **Cache Memory**: Utilizes Redis for efficient cache storage and faster response times.

## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js, Redis
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Real-Time Communication**: WebSockets
- **AI Integration**: Gemini API

## Getting Started

Follow the instructions below to get a copy of the project up and running on your local machine.

### Prerequisites

Before starting, make sure you have the following installed:

- Node.js (v14 or above)
- MongoDB
- Redis
- npm (Node Package Manager)

### Installation

#### 1. Clone the repository
```bash
git clone https://github.com/your-username/mern-collaborative-chat-ai.git
cd mern-collaborative-chat-ai
```

#### 2. Set up the backend
Go to the backend folder and install the dependencies:
```bash
cd backend
npm install
```

Create a `.env` file and add the following environment variables:
```
MONGODB_URI=your_mongo_connection_string
REDIS_HOST=localhost
REDIS_PORT=6379
JWT_SECRET=your_jwt_secret_key
GEMINI_API_KEY=your_gemini_api_key
```

Start the backend server:
```bash
npm start
```

#### 3. Set up the frontend
Go to the frontend folder and install the dependencies:
```bash
cd frontend
npm install
```

Start the frontend development server:
```bash
npm run dev
```

### Usage

- **Create a New Project**: After logging in, you can create a new project from the dashboard.
- **Add Collaborators**: For any project, you can invite collaborators via email or username.
- **Chat with Collaborators**: Once the collaborators join, you can chat with them in the project chatbox.
- **AI Assistant**: Type `@ai` followed by any query, and the AI will respond in the chat.

### Testing

To run tests for the backend, use the following command:
```bash
npm test
```

### Deployment

This project is ready for deployment on platforms like Heroku, Vercel, or AWS. Make sure to set up your environment variables on the cloud platform during deployment.

### Contributing

Feel free to fork the repository and submit pull requests. Contributions are always welcome!

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Gemini API** for providing the AI-powered assistant.
- **MongoDB** for the database.
- **Redis** for caching.
- **JWT** for authentication.
```
