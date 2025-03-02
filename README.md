# E-Commerce Management App

## Overview

E-Commerce Management App is a full-stack web application designed to facilitate online shopping, vendor management, and order processing. The project is built using **Spring Boot** for the backend and **React.js with Vite** for the frontend.

## Features

### Backend (Spring Boot)

- RESTful API for managing users, products, orders, and payments.
- Integration with MySQL database.
- User authentication and authorization using JWT.
- CRUD operations for products and orders.
- Vendor and customer management.
- H2 database for testing.

### Frontend (React.js + Vite)

- Responsive UI with Tailwind CSS.
- Product listing and filtering.
- Shopping cart functionality.
- User authentication with JWT.
- Order tracking and checkout process.

## Technologies Used

### Backend:

- Java 21 (or modify `pom.xml` for lower versions)
- Spring Boot 3
- Spring Security
- Hibernate ORM
- MySQL (or H2 for testing)
- Maven

### Frontend:

- React.js (Vite)
- Tailwind CSS
- Axios for API calls
- React Router for navigation

## Installation

### Prerequisites

- Install **Java 21** (or modify the project to use Java 17/11)
- Install **Node.js** (for frontend)
- Install **MySQL**

### Backend Setup

1. Navigate to the backend directory:
   ```sh
   cd ecommerce-backend/ecom-proj
   ```
2. Update the **application.properties** file with MySQL credentials.
3. Run the backend server:
   ```sh
   mvn clean install
   mvn spring-boot:run
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```sh
   cd ecommerce-frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```

## Troubleshooting

### Backend Issues

- **Java Version Error**: Modify `<release>21</release>` in `pom.xml` to a compatible version.
- **Database Connection Failure**: Ensure MySQL is running and credentials are correct in `application.properties`.

### Frontend Issues

- **Missing Scripts Error**: Ensure `package.json` contains the `start` script:
  ```json
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  }
  ```
  Use `npm run dev` instead of `npm start`.

## Future Enhancements

- Payment gateway integration.
- Admin dashboard for vendor management.
- AI-powered product recommendations.

## Project Image

### Home Page
![Image](https://github.com/user-attachments/assets/c1dc109e-dae4-4d7c-bbcd-a54a1c3e0bdc)

### Cart Page
![Image](https://github.com/user-attachments/assets/dfa61a3b-f05b-463b-8f8e-82b214cbf22d)

