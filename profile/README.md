# Welcome to the SteppingStones Project

SteppingStones is a comprehensive platform designed to simplify access to free and grant-funded business support opportunities for small and medium-sized enterprises (SMEs). The platform consists of a Business Admin Web-Portal and a Mobile Application, both of which are powered by a robust backend server. Our goal is to create a centralized hub where SMEs can easily find and take advantage of the resources they need to grow and succeed.

## Project Repositories

The SteppingStones project is divided into three main repositories, each focusing on a specific part of the system:

### 1. **Frontend Repository**
- **Framework:** [Next.js](https://nextjs.org/) (React)
- **Description:** This repository contains the source code for the Business Admin Web-Portal. The portal allows administrators to create and manage content, locations, notifications, and handle user feedback.
- **Key Features:**
  - Content Management System (CMS) for adding articles, videos, and ads.
  - Location and sub-location management.
  - Notification management to alert mobile users of new content.
  - Handling feedback and support requests from mobile users.
- **Technologies Used:**
  - Next.js (React)
  - Tailwind CSS for styling
  - Axios for API communication
  - ESLint and Prettier for code quality

### 2. **Backend Repository**
- **Framework:** [Express.js](https://expressjs.com/)
- **Database:** [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- **Description:** This repository contains the backend server that powers both the web portal and mobile application. The server handles user authentication, content management, notifications, and serves as the primary API endpoint for the frontend and mobile applications.
- **Key Features:**
  - RESTful API for content, user, and notification management.
  - User authentication using OAuth2.0 or JWT.
  - MongoDB Atlas for data storage, providing high availability and scalability.
  - Integration with third-party tools for notifications and analytics.
- **Technologies Used:**
  - Express.js (Node.js)
  - MongoDB Atlas for database management
  - Mongoose for object data modeling (ODM)
  - Passport.js for authentication
  - Jest for testing

### 3. **Mobile App Repository**
- **Framework:** [Expo](https://expo.dev/) (React Native)
- **Description:** This repository contains the source code for the SteppingStones mobile application. The app provides SMEs with access to a wide range of business support opportunities, personalized recommendations, and location-based search capabilities.
- **Key Features:**
  - Feed and local-feed screens to browse business support opportunities.
  - Location-based search for finding relevant opportunities in specific regions.
  - Push notifications to alert users about new opportunities and updates.
  - Ability to provide feedback, rate services, and manage subscriptions.
  - Accessibility features including contrast adjustment and screen reading.
- **Technologies Used:**
  - Expo (React Native)
  - React Navigation for navigation management
  - Redux for state management
  - Firebase Cloud Messaging (FCM) for push notifications
  - Jest and Detox for testing

## Project Structure

This project follows a microservices architecture, with each part of the application managed in its own repository. This approach allows for independent development, testing, and deployment of the frontend, backend, and mobile applications.

- **Frontend:** [`steppingstones-client`](https://github.com/MoreMediaTech/steppingstones-client)
- **Backend:** [`steppingstones-server`](https://github.com/MoreMediaTech/steppingstone-server)
- **Mobile App:** [`steppingstonesapp`](https://github.com/MoreMediaTech/steppingstonesapp)

## Getting Started

### Prerequisites
Before you begin, ensure you have the following tools installed:
- **Node.js** (v14.x or later)
- **npm** (v6.x or later)
- **MongoDB Atlas** account
- **Expo CLI** (for mobile app development)

### Installation

Each repository has its own `README.md` file with detailed instructions on how to set up the development environment, install dependencies, and run the application.

### Contribution Guidelines

We welcome contributions from the community! Please refer to the `CONTRIBUTING.md` file in each repository for guidelines on how to contribute to the project.

### License

This project is licensed under the MIT License. See the `LICENSE` file in each repository for more details.

## Contact

If you have any questions, feedback, or need support, please open an issue in the relevant repository, or reach out to our support team at [support@buildwithequilibrium.com](mailto:support@buildwithequilibrium.com).

---

Thank you for your interest in SteppingStones. Together, we can help SMEs access the support they need to thrive!
