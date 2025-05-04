
# Disaster Management System - A solution for monitoring the nature's causes.
 
The Disaster Management System is a full-stack web application designed to support effective disaster response, coordination, and communication. Built with the MERN stack (MongoDB, Express.js, React, Node.js), it empowers communities, volunteers, and authorities to collaborate efficiently during emergencies.

## Overview

This platform aims to bridge the gap between affected individuals and relief providers by offering a centralized, real-time system for managing disaster-related data and resources. It allows users to report incidents, disseminate important updates, coordinate volunteer efforts, and manage aid distribution across affected regions.

## Features

- **Real-time Disaster Updates**: Users receive timely alerts and status reports during ongoing disaster situations.
- **Incident Reporting**: Affected individuals can submit incident reports with location, type, and description, enabling authorities to assess and act quickly.
- **Volunteer Management**: Facilitates the registration, tracking, and coordination of volunteers offering on-ground support.
- **Community Interaction**: Users can form or join communities based on geographic or interest-based criteria to coordinate localized support.
- **Resource Allocation**: Administrators can manage inventory, distribute relief supplies, and track resource needs.
- **Emergency Contacts**: Provides a directory of critical helpline numbers and support services.
- **Administrative Dashboard**: A centralized control panel for monitoring reports, users, volunteers, and logistics in real time.

## Technology Stack

- **Frontend**: React.js, Redux, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT-based secure user authentication
- **Deployment**: Configurable for platforms like Heroku, Render, or Vercel

## Project Structure

```
Disaster-Management-System/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/     # UI components (modals, forms, etc.)
│   │   ├── pages/          # Page-level components (login, dashboard, reports)
│   │   └── App.js          # Main app entry point
├── server/                 # Node.js backend
│   ├── controllers/        # Application logic and handlers
│   ├── models/             # Mongoose schemas
│   ├── routes/             # Express route definitions
│   └── index.js            # Server entry point
├── .env.example            # Sample environment variable configuration
└── README.md
```

## Getting Started

### Prerequisites

- Node.js and npm
- MongoDB (local instance or MongoDB Atlas)
- Git

### Installation

**1. Clone the repository**
```bash
git clone https://github.com/sanikarajguru1509/Disaster-Management-System.git
cd Disaster-Management-System
```

**2. Setup the backend**
```bash
cd server
npm install
# Configure environment variables based on .env.example
npm start
```

**3. Setup the frontend**
```bash
cd client
npm install
npm start
```

## Security Considerations

- Passwords are hashed and stored securely using industry-standard encryption.
- JWT tokens are used for authentication and session management.
- Routes are protected based on user roles (admin, volunteer, user).

## Contributing

Contributions are welcome. Developers interested in improving the system or extending its capabilities are encouraged to fork the repository and open pull requests with detailed descriptions of changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For questions, feedback, or collaboration opportunities, please open an issue or contact the maintainer directly via GitHub.
