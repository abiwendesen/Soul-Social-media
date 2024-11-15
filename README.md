# Social Media App

A social media platform built with the MERN stack, allowing users to create accounts, share posts, like, and comment on posts. The app emphasizes responsiveness and modern design practices, ensuring a seamless user experience across devices.

---

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

---

## Features
- **User Authentication**: Secure account creation and login.
- **Post Creation**: Users can create, edit, and delete posts.
- **Interactive Features**: Like and comment on posts.
- **Responsive Design**: Optimized for all screen sizes using CSS Grid and Flexbox.
- **Media Storage**: Image upload and hosting via Cloudinary.

---

## Technologies Used
### Frontend
- **Semantic HTML5 Markup**
- **CSS Custom Properties**
- **CSS Grid and Flexbox**
- **React**: Component-based UI library.
- **React Redux**: State management for the application.
- **React Router**: Navigation and routing.

### Backend
- **Node.js**: JavaScript runtime for server-side development.
- **Express.js**: Lightweight framework for creating REST APIs.
- **MongoDB**: NoSQL database for storing user data, posts, and interactions.
- **Cloudinary**: Media storage and delivery for user-uploaded images.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/social-media-app.git
   cd social-media-app
   ```
2. Install dependencies:
   - For the frontend:
     ```bash
     cd client
     npm install
     ```
   - For the backend:
     ```bash
     cd server
     npm install
     ```
3. Set up environment variables:
   - Create a `.env` file in the `server` directory and add the following:
     ```env
     PORT=5000
     MONGO_URI=your-mongodb-connection-string
     CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
     CLOUDINARY_API_KEY=your-cloudinary-api-key
     CLOUDINARY_API_SECRET=your-cloudinary-api-secret
     JWT_SECRET=your-jwt-secret
     ```

4. Start the development servers:
   - Backend:
     ```bash
     cd server
     npm run dev
     ```
   - Frontend:
     ```bash
     cd client
     npm start
     ```

---

## Usage
1. Navigate to the app's homepage.
2. Sign up for an account or log in.
3. Create posts by clicking the "Create Post" button and uploading images or text.
4. Interact with posts by liking or commenting.

---

## Configuration
Ensure the following environment variables are configured in your `.env` file:
- **MongoDB**: Connection string for the database.
- **Cloudinary**: API credentials for image hosting.
- **JWT Secret**: Secret key for token generation and validation.

---

## Dependencies
### Frontend
- React
- Redux
- React Router DOM
- CSS Modules or Styled Components (if applicable)

### Backend
- Express.js
- MongoDB
- Cloudinary
- JSON Web Token (JWT)
- Mongoose

---


---


## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Enjoy building and enhancing your social media app! 🚀
