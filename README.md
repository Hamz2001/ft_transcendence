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

2. **Standard User Management**:
   - Secure user registration and authentication.
   - Unique display names and avatar uploads.
   - Friend system with online status tracking.

3. **Database Management**:
   - Utilized Django ORM to structure and query the PostgreSQL database efficiently.
   - Ensured database consistency across services.

4. **Friend Notifications**:
   - Implemented features for sending, accepting, refusing, and removing friend requests.
   - Ensured real-time updates for friend notifications using WebSockets.

5. **Containerization**:
   - Built Docker images for individual services.
   - Configured Docker Compose for multi-container orchestration.

6. **Security**:
   - HTTPS enforced for secure communication.
   - Protection against SQL injection and XSS attacks.
   - Password hashing and sensitive data management using .env files.

7. **Two-Factor Authentication (2FA) and JWT**:
   - Enhanced security with Two-Factor Authentication options.
   - Used JSON Web Tokens (JWT) for secure session management.

   ** Team **
      - Hallal Khalifa: @khallal42
      - Me: @Hamz2001
      - Mohcine Majdoubi: @Happy4mou
      - Mouad Ajmani: @majmani1
      - MOURAD EL MARSSI : @Mel-Marssi
