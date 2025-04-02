# Real-Time Chat Application

## Overview
The **Real-Time Chat Application** is a WebSocket-based project that enables instant messaging between users. Built using **Spring Boot** for the backend and a suitable frontend, this application provides a seamless and interactive chat experience.

## Tech Stack
- **Backend:** Spring Boot (Java)
- **Frontend:** (HTML, CSS, JS)
- **WebSocket Protocol:** STOMP (Simple Text Oriented Messaging Protocol)
- **Message Broker:** RabbitMQ / ActiveMQ (if applicable)

## Features
- Real-time bi-directional communication using WebSockets
- group messaging
- Online user status tracking
- Typing indicators

## Installation & Setup
### Prerequisites
- Java 17+
- Spring Boot
- Node.js & npm (if using React/Angular frontend)
- RabbitMQ (if using a message broker)

### Backend Setup
```sh
cd backend
mvn clean install
mvn spring-boot:run
```

### Frontend Setup
```sh
cd frontend
npm install
npm start
```

## WebSocket Endpoints
| Endpoint | Description |
|----------|-------------|
| `/ws/chat` | Main WebSocket connection endpoint |
| `/topic/messages` | Broadcast messages to all connected users |
| `/queue/messages/{userId}` | Private messaging between users |

## Future Enhancements
- Message history storage
- User authentication (JWT-based, if implemented)
- End-to-end encryption for messages
- WebRTC for voice/video chat integration
- AI-based smart replies

## Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request.

## License
MIT License

---
### Author
**Himanshu Rawat**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-rawat20)  |  [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/himanshur1234)  |  [![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=web&logoColor=white)](https://portfolio-ten-sigma-22.vercel.app/)
