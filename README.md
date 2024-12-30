# E-COMMERCE WEBSITE

**COMPANY**: CODTECH IT SOLUTIONS 

**NAME**: KRISHNA MER 

**INTERN ID**: CT12WDUC 

**DOMAIN** : MERN STACK WEB DEVELOPMENT  

**BATCH DURATION**: DECEMBER 17th, 2024 to MARCH 17th, 2025  

Backend 

API Documentation for Ecommerce Project API with Node.js and Express
Welcome to the documentation for the Ecommerce Project API! This API provides a set of endpoints and functionalities to interact with our eCommerce platform programmatically. With this API, you can build applications, integrations, and automate various tasks related to our online store.

Base URL: http://localhost:5454

Authentication
All protected endpoints require the Authorization header with a valid token.

Endpoints
Update Cart Item
URL: /api/cart_items/{cartItemId}
Method: PUT
Tags: cart-item-controller
Request Parameters:
cartItemId (integer, int64, required)
Request Headers:
Authorization (string, required)
Request Body:
{
  "$ref": "#/components/schemas/CartItem"
}
Responses:
200 OK
{
  "$ref": "#/components/schemas/CartItem"
}
Delete Cart Item
URL: /api/cart_items/{cartItemId}
Method: DELETE
Tags: cart-item-controller
Request Parameters:
cartItemId (integer, int64, required)
Request Headers:
Authorization (string, required)
Responses:
200 OK
{
  "$ref": "#/components/schemas/ApiResponse"
}
Add Item to Cart
URL: /api/cart/add
Method: PUT
Tags: cart-controller
Request Headers:
Authorization (string, required)
Request Body:
{
  "$ref": "#/components/schemas/AddItemRequest"
}
Responses:
200 OK
{
  "$ref": "#/components/schemas/ApiResponse"
}
... (continue documenting other endpoints)

Components
Schemas
CartItem
ApiResponse
AddItemRequest
Product
Order
User
AuthResponse
ReviewRequest
Review
RatingRequest
Rating
PaymentLinkResponse
Address
CreateProductRequest
PageProduct
Servers
Server 1:
URL: http://localhost:5454
Description: Generated server URL

# Shop With Zosh - E-Commerce Platform

A modern e-commerce platform built with React, featuring a clean UI and seamless shopping experience for ethnic wear and fashion.

## Features

### Homepage & Navigation
- Clean and intuitive navigation bar with Women, Men, Company, and Stores sections
- User profile section and cart status indicator
- Prominent free delivery banner for orders over $100
- Beautiful hero section featuring "Celestial Bridals" with designer lehengas promotion

### Product Browsing
- Grid-based product display with clear categorization
- Comprehensive filtering system including:
  - Color selection
  - Size options
  - Price ranges
  - Discount ranges
  - Availability filters
- Product sorting functionality

### Product Details
- Detailed product cards displaying:
  - High-quality product images
  - Product name and brand (e.g., ALLEN SOLLY)
  - Original and discounted prices
  - Size selection (S, M, L)
  - Customer ratings and reviews
  - Comprehensive product descriptions
  - "Add to Cart" functionality

### Shopping Cart
- Clear cart summary with product details
- Quantity adjustment controls
- Price breakdown including:
  - Item subtotal
  - Applied discounts
  - Delivery charges
  - Total amount
- Prominent checkout button

### Checkout Process
1. Address Collection
   - Form for shipping details
   - Fields for name, address, city, state, and PIN code
   - Phone number verification
   - Address save functionality

2. Order Summary
   - Detailed breakdown of items
   - Price calculations
   - Delivery information

3. Payment Integration
   - Secure payment processing through Razorpay
   - Multiple payment options
   - Order confirmation and success page

### Mobile Responsiveness
- Fully responsive design
- Optimized for all screen sizes
- Touch-friendly interface

## Technical Features
- Real-time cart updates
- Form validation
- Secure payment processing
- Optimized image loading
- State management for cart items
- User session handling

## Future Enhancements
- Wishlist functionality
- Enhanced search capabilities
- Order tracking system
- User reviews and ratings
- Size guide integration
- Social sharing options

![Screenshot (2002)](https://github.com/user-attachments/assets/594c7cae-0b22-437e-9d3f-74c8e09d3840)
![Screenshot (2003)](https://github.com/user-attachments/assets/6838c4ef-18ae-4f46-8fc6-fa9846a1a0f0)
![Screenshot (2004)](https://github.com/user-attachments/assets/ddfd61a2-9a21-435c-bb84-298ffb6f4064)
![Screenshot (2006)](https://github.com/user-attachments/assets/c6ec4273-23c4-4904-81f7-c160bea5c07e)
![Screenshot (2009)](https://github.com/user-attachments/assets/b25eb30c-8b77-4663-8fe9-e4f3af99b310)
![Screenshot (2008)](https://github.com/user-attachments/assets/ddbb9a8c-a39d-4ad1-9bc1-ae15d009364a)
![Screenshot (2010)](https://github.com/user-attachments/assets/efbab854-3e23-4bb6-9437-dca2c2d8766f)
![Screenshot (2007)](https://github.com/user-attachments/assets/e8b718cc-87ad-450e-85fa-ad43f00816c5)
![Screenshot (2011)](https://github.com/user-attachments/assets/13ad6693-7098-44b5-bbdf-9aee780a6d0e)
![Screenshot (2005)](https://github.com/user-attachments/assets/67e9f8b2-1ccd-4cc2-9ca9-e0dc4c2b7b35)
![Screenshot (2012)](https://github.com/user-attachments/assets/14198e2e-1b04-4b7a-817a-c9d766ef2502)
