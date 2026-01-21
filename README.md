## BidPoint
BidPoint is a full-stack auction platform that enables real-time bidding, item management, and personalized user experiences. Built with a focus on scalability and security, it leverages Spring Boot for a robust backend and React.js for a dynamic, responsive frontend.

## 🚀 Key Features
- Real-time Synchronized Bids: High-performance bidding system ensuring all users see the latest prices instantly without manual refreshes.
- Recommendation Algorithm: A custom logic layer that suggests items to users based on their bidding history and interests.
- Secure Authentication: Full JWT (JSON Web Token) implementation for stateless session management and secure API endpoints.
- Admin Dashboard: A dedicated interface for administrators to manage users, monitor active auctions, and handle platform-wide CRUD operations.
- Complete CRUD Functionality: Users can create, update, and delete item listings with integrated image and data persistence.

## 🛠 Tech Stack
Frontend
- Framework: React.js
- Language: JavaScript
- State Management: Redux
- Styling: Material UI

Backend
- Framework: Spring Boot (Java)
- Security: Spring Security & JWT
- Database: PostgreSQL
- Build Tool: Maven

## 🏗 Architecture
The project follows a decoupled client-server architecture:

- Client: Handles UI/UX and communicates via RESTful APIs.
- Server: Manages business logic, authentication filters, and database interactions.
- Synchronization: Utilizes [Insert technology e.g., WebSockets or Polling] to ensure bid concurrency.
