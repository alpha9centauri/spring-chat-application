# Real-Time Chat Application with WebSockets

### Overview

This project is a **Real-Time Chat Application** that enables users to connect, interact, and share messages in a live chat room environment. Built using **Java Spring Boot** and **React**, this application leverages **WebSocket** technology for instant messaging and real-time interactions. This chat app was designed to provide a smooth, responsive user experience and showcase my skills in full-stack development.

### Features

- **Real-Time Messaging**: Uses WebSockets to allow instantaneous message exchange, enabling smooth, uninterrupted communication.
- **Intuitive User Interface**: Developed with **React**, providing a sleek and user-friendly chat interface for enhanced user experience.
- **Interactive Chatbot Integration**: Can be integrated with OpenAI’s API for intelligent chatbot responses and image generation based on user prompts, making it ideal for versatile applications like customer support and community engagement.
- **User Identification**: Assigns unique colors to each user for easy message tracking and identification in the chat room.
- **Responsive Design**: Optimized for multiple devices with a design that adapts seamlessly to various screen sizes.

### Tech Stack

- **Backend**: Java Spring Boot, WebSocket with STOMP (Simple Text Oriented Messaging Protocol)
- **Frontend**: React, JavaScript, HTML5, CSS3
- **Real-Time Communication**: SockJS, Stomp.js for WebSocket support across browsers

### Architecture

This application follows a client-server architecture, where the **frontend** communicates with the **backend WebSocket server** through specific STOMP endpoints. The backend is configured to handle message broadcasting and user connections with simplicity and efficiency.

- **WebSocket Configurations**: Configured using Spring Boot’s WebSocketMessageBrokerConfigurer to support message handling and routing.
- **STOMP Endpoints**: Enables real-time communication by setting up `/topic` for broadcasting messages and `/app` for user interactions.

### How to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/alpha9centauri/spring-chat-application.git
   ```

2. **Backend Setup**:
   - Ensure **Java** and **Spring Boot** are installed.
   - Navigate to the project directory and start the Spring Boot server:
     ```bash
     ./mvnw spring-boot:run
     ```

3. **Frontend Setup**:
   - Navigate to the frontend directory.
   - Install dependencies and start the React application:
     ```bash
     npm install
     npm start
     ```

4. **Access the Application**:
   - Open a browser and go to `http://localhost:3000`.

### Potential Applications

- **Customer Support**: Real-time assistance for customers on e-commerce platforms or service websites.
- **Online Communities**: Ideal for community websites or forums that need interactive chat rooms.
- **Team Collaboration**: Enables real-time communication in workspaces, making it suitable for remote teams and project collaborations.

### Why This Project?

This application demonstrates proficiency in **full-stack development**, **real-time data handling**, and **WebSocket-based communication**. It highlights skills in creating robust, interactive, and responsive applications with a strong foundation in Spring Boot and React. This project is ideal for showcasing experience in **modern web development** and **real-time communication solutions**.

### Future Enhancements

- **User Authentication**: Add secure login for personalized chat sessions.
- **Chatbot Enhancements**: Integrate OpenAI for advanced chatbot interactions, including automated responses and image generation.
- **Group Chats & Private Messaging**: Expand functionality to support multiple rooms and private conversations.
- **Message Persistence**: Store messages for chat history across sessions.
