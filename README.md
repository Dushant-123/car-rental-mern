# Car Rental Booking Website

A full-stack car rental booking application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The platform provides a seamless car rental experience, allowing users to browse available vehicles, book cars, and manage reservations through a modern and responsive interface.

## Features

### Frontend

- React.js and Tailwind CSS for a modern, responsive user interface.
- User registration and login.
- Browse available cars and vehicle details.
- Search cars based on pickup location and rental dates.
- User-friendly car booking workflow.
- Personal booking history.
- Dedicated admin dashboard.

### Backend

- RESTful APIs built using Node.js and Express.js.
- MongoDB and Mongoose for database management.
- JWT-based authentication and authorization.
- User and administrator access management.
- Car inventory and booking management.
- ImageKit integration for image storage and optimization.

## Key Functionalities

### 1. User Authentication

- Secure registration and login.
- JWT-based authentication.
- Protected routes for authenticated users.

### 2. Car Listings

- Browse available rental cars.
- View vehicle details and rental prices.
- Search cars by location and rental dates.
- Check vehicle availability.

### 3. Booking System

- Select a vehicle and rental duration.
- Create car reservations.
- View personal booking history.
- Track booking status.

### 4. Admin Dashboard

- Add new cars to the inventory.
- Manage existing car listings.
- Manage vehicle availability.
- View and manage customer bookings.

### 5. Media Management

- Upload vehicle images using ImageKit.
- Optimized image delivery.
- Cloud-based image storage.

## Tech Stack

### Frontend

- React.js
- JavaScript
- Tailwind CSS
- HTML5
- CSS3

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Tokens (JWT)
- ImageKit

### Development Tools

- Git
- GitHub
- npm
- Visual Studio Code

## System Architecture

```text
React Frontend
      |
      | REST APIs
      v
Node.js + Express.js
      |
      +---- MongoDB Database
      |
      +---- JWT Authentication
      |
      +---- ImageKit Cloud Storage
```

## Getting Started

### Prerequisites

- Node.js
- npm
- MongoDB
- ImageKit account

### Clone the Repository

```bash
git clone https://github.com/Dushant-123/car-rental-mern.git
cd car-rental-mern
```

### Backend Setup

Navigate to the backend directory and install dependencies.

```bash
cd server
npm install
```

Create a `.env` file and configure the required environment variables.

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
IMAGEKIT_PUBLIC_KEY=your_public_key
IMAGEKIT_PRIVATE_KEY=your_private_key
IMAGEKIT_URL_ENDPOINT=your_url_endpoint
```

Start the backend server.

```bash
npm run server
```

### Frontend Setup

Open a separate terminal.

```bash
cd client
npm install
npm run dev
```

Open the local application URL displayed in the terminal.

## Security

- JWT-based authentication.
- Protected API endpoints.
- User and administrator authorization.
- Environment-based secret management.

## Future Enhancements

- Online payment gateway integration.
- Email booking confirmations.
- Customer ratings and reviews.
- Advanced search and filtering.
- Automated booking reminders.
- Docker-based deployment.
- AI-powered vehicle recommendations.

## Learning Outcomes

This project provided practical experience in:

- Full-stack web development.
- RESTful API design and implementation.
- Database modeling.
- Authentication and authorization.
- Cloud-based media management.
- Responsive frontend development.
- Version control using Git and GitHub.
- End-to-end application development.

## Author

**Dushant Bhola**

- GitHub: https://github.com/Dushant-123
- National Institute of Technology, Kurukshetra

## Acknowledgements

This project was developed as a hands-on learning project to strengthen full-stack development skills using the MERN stack.
 
