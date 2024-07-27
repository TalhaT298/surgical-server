# Surgical Server

SurgicalSavvy Server is a backend service built with Node.js, Express, and MongoDB. This project is designed to manage surgical services and orders, providing a RESTful API for interacting with the data.

## Features

- **Service Management**: Retrieve and manage surgical services.
- **Order Management**: Handle orders with CRUD operations.
- **Environment Variables**: Securely manage sensitive data.
- **CORS Enabled**: Support for Cross-Origin Resource Sharing.
- **Modular Design**: Organized codebase for scalability.

## Endpoints

### Services

- **Get All Services**
- GET /services

- **Get Service by ID**
GET /services/

### Orders

- **Get All Orders**
GET /orders

- **Get Orders by Email**
GET /orders?email=user@example.com


- **Create New Order**
POST /orders

- **Update Order Status**
PATCH /orders/

- **Delete Order**

## Setup

1. Clone the repository:

 ```bash
 git clone https://github.com/yourusername/surgical-server.git
 cd surgical-server
```
2. Install dependencies:
```
npm install
```
Dependencies
- express
- cors
- dotenv
- mongodb

## Live Link <https://surgicalsavvy.netlify.app/>
