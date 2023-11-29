# E-Commerce Backend API

This project is a robust and feature-rich backend API for an E-Commerce platform, providing the foundation for building mobile or web-based E-Shop applications. It is designed to offer a comprehensive set of functionalities to enhance the shopping experience for users.

## Features

### 1. Real World Backend RESTful API

Built on RESTful principles, this API provides a scalable and maintainable solution for handling various aspects of an E-Commerce platform.

### 2. Authentication and Authorization

- **Login & Register Users:** Utilizes JWT (JSON Web Token) authentication for secure user authentication and registration.

### 3. Password Management

- **Password Forgot/Reset:** Allows users to reset their passwords through a secure and user-friendly process.
- **Confirmation Email on Signup:** Sends confirmation emails to users upon successful registration.

### 4. Advanced Searching, Sorting, Pagination, and Filtering

Enhanced search capabilities, sorting options, pagination, and filtering mechanisms ensure a seamless browsing experience for users.

### 5. Star Rating System

Incorporates a star rating system for products, enabling users to provide feedback and make informed purchase decisions.

### 6. Discount Coupon Code

Supports the application of discount coupon codes during checkout, providing users with promotional benefits.

### 7. Cart and Wishlist Functionality

- **Adding Products to Cart:** Users can add products to their shopping cart for convenient checkout.
- **Adding Products to Wishlist:** Allows users to save products for future consideration.

### 8. Payment Methods

- **Cash on Delivery:** Provides a cash on delivery option for users who prefer to pay upon receiving the products.
- **Credit Card Payment with Stripe:** Integrates with Stripe for secure credit card transactions.

### 9. Image Handling

- **Image Upload:** Supports single and multiple image uploads for product images.
- **Image Processing:** Implements image processing to ensure optimal quality and size.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ecommerce-backend-api.git
   cd ecommerce-backend-api
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   - Create a `.env` file.
   - Add the necessary variables, including database connection details, JWT secret, Stripe API key, etc.

4. Run the server:

   ```bash
   npm start
   ```

5. The API will be accessible at `http://localhost:3000`.

Happy building your E-Commerce platform! 🛍️
