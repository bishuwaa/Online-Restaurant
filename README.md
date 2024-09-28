# Restaurant Management Application

A full-stack restaurant management application built using Node.js, Express.js, and MongoDB. This application provides a complete REST API for user authentication, restaurant management, category and food management, and order tracking.

## Features

- **Authentication**: Token-based user authentication using JWT.
- **User Management**:
  - Get user details.
  - Update user profile.
  - Reset password.
  - Delete account.
- **Restaurant Management**:
  - Create a new restaurant.
  - Get all restaurants.
  - Get a restaurant by its ID.
  - Delete a restaurant.
- **Category Management**:
  - Create a new category.
  - Get all categories.
  - Update a category.
  - Delete a category.
- **Food Management**:
  - Create a new food item.
  - Get all food items.
  - Get a specific food item by ID.
  - Get food items by restaurant ID.
  - Update a food item.
  - Delete a food item.
- **Order Management**:
  - Place an order.
  - Check order status.

## Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)

## API Endpoints

### Authentication
- **POST** `/auth/login` - Login and receive a token.

### User
- **GET** `/users/:id` - Get user details.
- **PUT** `/users/:id` - Update user details.
- **POST** `/users/reset-password` - Reset user password.
- **DELETE** `/users/:id` - Delete user account.

### Restaurant
- **POST** `/restaurants` - Create a new restaurant.
- **GET** `/restaurants` - Get all restaurants.
- **GET** `/restaurants/:id` - Get a restaurant by its ID.
- **DELETE** `/restaurants/:id` - Delete a restaurant.

### Category
- **POST** `/categories` - Create a new category.
- **GET** `/categories` - Get all categories.
- **PUT** `/categories/:id` - Update a category.
- **DELETE** `/categories/:id` - Delete a category.

### Food
- **POST** `/foods` - Create a new food item.
- **GET** `/foods` - Get all food items.
- **GET** `/foods/:id` - Get a specific food item by ID.
- **GET** `/foods/restaurant/:restaurantId` - Get food items by restaurant ID.
- **PUT** `/foods/:id` - Update a food item.
- **DELETE** `/foods/:id` - Delete a food item.

### Order
- **POST** `/orders` - Place an order.
- **GET** `/orders/:id` - Get order status.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/bishuwaa/Online-Restaurant.git

# Online-Restaurant
