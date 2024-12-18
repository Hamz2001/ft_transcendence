# ft_transcendence

ft_transcendence is a full-stack web application leveraging microservice architecture, built to provide a seamless gaming and social experience. The project is containerized with Docker, integrating Django for the back-end, PostgreSQL for data management, and WebSockets for real-time communication.

## Features
- Real-time chat system using WebSockets.
- Online multiplayer game powered by the Canvas API.
- User authentication and authorization, including Two-Factor Authentication (2FA).
- Dynamic front-end built with HTML, CSS, JavaScript, and Bootstrap.
- Scalable microservices for modular functionality.
- Configured Nginx as a reverse proxy for load balancing and routing.
- Deployed services efficiently in a Dockerized environment.

## Technologies Used
- **Frameworks**: Django, Django Channels
- **Database**: PostgreSQL
- **Containerization**: Docker
- **Server**: Nginx (as a reverse proxy)
- **Front-End**: HTML, CSS, JavaScript, Bootstrap
- **API**: Django REST Framework

## Responsibilities
As the **Back-End Developer**, my key tasks included:
1. **Microservice Architecture**:
   - Designed and implemented modular back-end services for user management.

2. **Database Management**:
   - Utilized Django ORM to structure and query the PostgreSQL database efficiently.
   - Ensured database consistency across services.

3. **Friend Notifications**:
   - Implemented features for sending, accepting, refusing, and removing friend requests.
   - Ensured real-time updates for friend notifications using WebSockets.

4. **User Authentication**:
   - Implemented JWT-based authentication and 2FA for enhanced security.
   - Integrated OAuth 42- and Google for single sign-on (SSO).

5. **Containerization**:
   - Built Docker images for individual services.
   - Configured Docker Compose for multi-container orchestration.
