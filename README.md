# Mini E-commerce API

This is a simple API for managing products in a mini e-commerce application.

## Features
- Add new products
- Get all products
- Get a single product by ID

## Technologies Used
- Node.js
- Express.js
- MongoDB with Mongoose

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/mini-ecommerce-api.git
```
2. Navigate into the project folder:
```bash
cd mini-ecommerce-api
```
3. Install dependencies:
```bash
npm install
```

## Environment Variables
Create a `.env` file in the root directory and add:
```
MONGO_URI = 'your_mongodb_connection_string'
PORT = 5000
```

## Running the API
Start the server with:
```bash
npm start
```

## API Endpoints
### 1. Get All Products
```http
GET /api/v1/products
```
Response:
```json
{
  "success": true,
  "products": [ ... ]
}
```
![Get All Products](https://github.com/Santhosh1015/Basic_APIs/blob/main/api_basci.png?raw=true)


### 2. Get Single Product
```http
GET /api/v1/product/:id
```
Response:
```json
{
  "success": true,
  "product": { ... }
}
```
![Get Single Product](https://github.com/Santhosh1015/Basic_APIs/blob/main/api_basic2.png?raw=true)

### 3. Create Product
```http
POST /api/v1/product
```
Request Body:
```json
{
  "name": "Product Name",
  "price": "100",
  "description": "Product Description"
}
```
![Create Product](https://github.com/Santhosh1015/Basic_APIs/blob/main/api_basic3.png?raw=true)



## License
This project is licensed under the MIT License.

By
Santhosh R

---

