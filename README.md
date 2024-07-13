# E-Commerce Website Clone

Welcome to the E-Commerce Website Clone project! This is a full-stack web application that mimics the functionalities of popular e-commerce platforms like Flipkart. It is built using modern web technologies including React for the frontend, Node.js for the backend, and MongoDB for the database.


## Project Overview

This project is a web application that allows users to browse products, add items to the cart, and place orders. It includes features for user authentication, product management, and order processing. 

## Features

- **User Authentication**: Sign up, log in, and manage user accounts.
- **Product Browsing**: View products with options for filtering and sorting.
- **Shopping Cart**: Add, update, or remove items from the cart.
- **Order Management**: Checkout process including order summary and confirmation.
- **Admin Panel**: Manage products, view orders, and update product details.
- **Responsive Design**: Optimized for desktop and mobile devices.

## Tech Stack

- **Frontend**: [React](https://reactjs.org/)
- **Backend**: [Node.js](https://nodejs.org/) with [Express](https://expressjs.com/)
- **Database**: [MongoDB](https://www.mongodb.com/)
- **Authentication**: [JWT](https://jwt.io/)
- **Styling**: [CSS](https://www.w3.org/Style/CSS/) with [Bootstrap](https://getbootstrap.com/)

## Installation

### Frontend

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/ecommerce-website-clone.git
    cd ecommerce-website-clone
    ```

2. Navigate to the `frontend` directory:

    ```bash
    cd frontend
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Start the frontend server:

    ```bash
    npm start
    ```

   The React application should now be running at `http://localhost:3000`.

### Backend

1. Navigate to the `backend` directory:

    ```bash
    cd ../backend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up environment variables:
   
   Create a `.env` file in the `backend` directory with the following content:

    ```env
    MONGO_URI=mongodb://localhost:27017/ecommerce
    JWT_SECRET=your_jwt_secret
    ```

4. Start the backend server:

    ```bash
    npm start
    ```

   The Node.js server should now be running at `http://localhost:5000`.

## Usage

1. Open your web browser and navigate to `http://localhost:3000` to access the frontend of the application.
2. Use the provided interfaces to sign up, log in, browse products, add items to your cart, and place orders.
3. For administrative tasks, you can access the admin panel through the admin dashboard (accessible after logging in as an admin).

