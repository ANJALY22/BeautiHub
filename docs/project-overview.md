# BeautiHub — Project Overview

## 1. Problem Statement

Finding suitable beauty products and understanding how to use them can be difficult for users.

Users often have to search through multiple websites, compare products manually, and rely on scattered information about skin types, concerns, ingredients, and product suitability.

BeautiHub aims to provide a simple and organized platform where users can explore beauty products, understand their suitability, and make better beauty-related decisions.

## 2. Project Objective

The objective of BeautiHub is to create a user-friendly beauty platform that brings beauty product discovery and personalized recommendations into one application.

The application should provide:

- Easy product discovery
- Product information
- Beauty recommendations
- Search and filtering
- Personalized user experience
- Simple and attractive UI

## 3. Target Users

### Primary Users

- People looking for skincare and beauty products
- Users who want recommendations based on their needs
- Users who want to explore different beauty products
- Beginners who need simple beauty guidance

### Secondary Users

- Beauty enthusiasts
- Users comparing different products
- Users looking for products for specific beauty concerns

## 4. Main Features

### User Features

- User registration and login
- User profile
- Product browsing
- Product search
- Product filtering
- Product details
- Beauty recommendations
- Favorites/wishlist
- Personalized recommendations

### Product Information

Each product can contain:

- Product name
- Brand
- Category
- Description
- Ingredients
- Suitable skin type
- Beauty concerns
- Price
- Product image
- Rating

### Future Features

- Reviews and ratings
- AI-powered recommendations
- Personalized skincare routine
- Product comparison
- Shopping/cart functionality
- Notifications

## 5. Technology Stack

### Frontend

- React
- JavaScript
- HTML
- CSS
- Vite

### Backend

- Java
- Spring Boot
- REST APIs

### Database

- PostgreSQL

### Development Tools

- Git
- GitHub
- VS Code / IntelliJ IDEA
- Postman

## 6. High-Level Architecture

BeautiHub will follow a client-server architecture.

```text
                 ┌───────────────────┐
                 │      User         │
                 └─────────┬─────────┘
                           │
                           ▼
                 ┌───────────────────┐
                 │ React Frontend    │
                 │       UI          │
                 └─────────┬─────────┘
                           │
                      REST APIs
                           │
                           ▼
                 ┌───────────────────┐
                 │ Spring Boot       │
                 │ Backend           │
                 └─────────┬─────────┘
                           │
                           ▼
                 ┌───────────────────┐
                 │   PostgreSQL      │
                 │    Database       │
                 └───────────────────┘