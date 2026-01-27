Car Rental Web Application (MERN Stack)

A full-stack Car Rental Web Application built using the MERN stack (MongoDB, Express, React, Node.js). The application allows users to browse cars, book rentals for selected dates, and manage reservations, while providing admin-level controls for managing vehicles and bookings.

 Project Overview

This application simulates a real-world car rental platform where users can:

Create an account and log in securely

Browse available cars with images and details

Select rental dates and book cars

View their booking history

Manage cars and bookings through admin access

The project focuses on building complete end-to-end functionality, from frontend UI to backend APIs and database integration.

✨ Features
 User Features

User authentication (Signup & Login)

Browse available cars

Book cars for selected dates

View personal booking history

 Admin Features

Add new cars with images

Update or delete car listings

View and manage all bookings

 Core Functionalities

RESTful APIs for users, cars, and bookings

Secure authentication using JWT

Image upload and optimization

Responsive UI across devices

 Tech Stack
Frontend

React.js

Tailwind CSS

Axios

Backend

Node.js

Express.js

MongoDB + Mongoose

JSON Web Tokens (JWT)

ImageKit

 Project Structure
car-rental-mern/
├── client/
├── server/
├── .env
├── .gitignore
└── README.md

Installation & Setup
Clone the Repository
git clone https://github.com/your-username/car-rental-mern.git
cd car-rental-mern

Backend Setup
cd server
npm install


Create a .env file:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
IMAGEKIT_PUBLIC_KEY=your_public_key
IMAGEKIT_PRIVATE_KEY=your_private_key
IMAGEKIT_ENDPOINT=your_endpoint


Start the backend:

npm run dev

Frontend Setup
cd client
npm install
npm start


The application will run at:

http://localhost:3000

Learning Outcomes

Implemented REST APIs for a real-world application

Integrated frontend and backend using Axios

Implemented authentication using JWT

Structured a scalable MERN stack project

Handled image uploads and optimization

Implemented booking logic using date-based availability

 Future Enhancements

Payment gateway integration

Advanced search and filters

Email notifications for bookings

Admin analytics dashboard
