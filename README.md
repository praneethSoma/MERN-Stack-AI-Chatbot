# AI Chatbot with MERN Stack and OpenAI Integration

## Project Overview
This project is a full-stack AI chatbot application built using the MERN (MongoDB, Express.js, React, Node.js) stack, inspired by the tutorial from [JavaScript Mastery](https://youtu.be/PX_YOfEdhRg?si=Irpl7ydBuiOiomad). It features a comprehensive user authentication system, OpenAI integration, and a responsive chat interface.

## Key Features
- MERN Stack implementation (MongoDB, Express.js, React, Node.js)
- User Authentication and Authorization System
- Express-Validators middleware for data validation
- MongoDB integration for storing user chats
- Custom authentication system with JWT and HTTP-only cookies
- Protected user routes with verification checks
- Modern React app built with Vite
- Beautiful and responsive chat UI using Material UI
- OpenAI integration for AI-powered responses
- User session management

## Technologies Used
- MongoDB: Database for storing user information and chat history
- Express.js: Backend framework
- React: Frontend library (built with Vite)
- Node.js: Runtime environment
- Material UI: For designing the user interface
- JWT (JSON Web Tokens): For secure authentication
- OpenAI API: For generating AI responses
- Express-Validator: For input validation

## Usage
1. Register a new account or log in to an existing one
2. Once logged in, you'll be directed to the chat interface
3. Start a conversation with the AI chatbot
4. Your chat history will be saved and can be accessed in future sessions

## API Endpoints
- `/api/auth/signup`: Register a new user
- `/api/auth/login`: User login
- `/api/auth/logout`: User logout
- `/api/chat`: Send and receive chat messages

## Future Improvements
- Implement real-time chat updates using Socket.io
- Add support for multiple chat sessions
- Enhance the AI model with fine-tuning for specific use cases

