## E-commerce Web Application Documentation

## Overview
The E-commerce Web Application is a comprehensive online shopping platform designed with Angular, TypeScript, Bootstrap, and HTML for the frontend, and Java Spring Boot, JDBC, and other tools for the backend. This application demonstrates the ability to design and implement a scalable and efficient e-commerce solution.
Technical Specifications

## Frontend:
Framework: Angular 14
Programming Language: TypeScript 4.7
UI Framework: Bootstrap 5
Template Engine: HTML 5

## Backend:
Framework: Java Spring Boot 2.7.2
Programming Language: Java 8
Database: MySQL 8.0
Tools: Spring Data JPA, Maven, Git


## System Essence
The E-commerce Web Application is designed to:
User Management: Register, login, and manage user accounts.
Product Management: Create, edit, and manage products, including categories and subcategories.
Order Management: Place, process, and manage orders, including payment and shipping.
Shopping Cart: Add, remove, and manage products in the shopping cart.
Payment Gateway: Integrate with payment gateways for secure transactions.
Search and Filter: Search products by keyword, category, and price.
Product Reviews: Add, edit, and manage product reviews and ratings.

## Database Schema
The database schema consists of the following entities:
Users: User information, including name, email, and password.
Products: Product information, including name, description, price, and category.
Orders: Order information, including date, total, and status.
Order Items: Product items in each order.
Payments: Payment information, including method and transaction ID.
Reviews: Product reviews and ratings.

## API Endpoints
The application exposes the following API endpoints:
/users: Retrieve a list of users or create a new user.
/products: Retrieve a list of products or create a new product.
/orders: Retrieve a list of orders or create a new order.
/order-items: Retrieve a list of order items or create a new order item.
/payments: Retrieve a list of payments or create a new payment.
/reviews: Retrieve a list of reviews or create a new review.

## Security
Spring Security ensures secure authentication and authorization for the backend. Role-based access control is implemented to restrict access to certain features and data.
Frontend Integration
The frontend developer can integrate the backend solution by calling the exposed API endpoints using HTTP requests. For example, to retrieve a list of products, the frontend can send a GET request to /products.

## Usefulness
The E-commerce Web Application provides a comprehensive online shopping platform, enabling:
Online Shopping: Browse and purchase products online.
User-Friendly Interface: Easy-to-use interface for users and administrators.
Secure Transactions: Integrate with payment gateways for secure transactions.
Product Management: Easily manage products, categories, and subcategories.
Order Management: Efficiently manage orders, including payment and shipping.
