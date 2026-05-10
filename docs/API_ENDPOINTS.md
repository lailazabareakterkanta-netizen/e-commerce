# E-Commerce API Documentation

## Base URL
```
http://localhost:5000/api
```

## Authentication
All protected endpoints require JWT token in header:
```
Authorization: Bearer <token>
```

## Endpoints

### Users
- `POST /users/register` - Register new user
- `POST /users/login` - Login user
- `GET /users/profile` - Get user profile (protected)

### Products
- `GET /products` - Get all products
- `GET /products/:id` - Get single product
- `GET /products/category/:categoryId` - Get products by category
- `POST /products` - Create product (admin only)
- `PUT /products/:id` - Update product (admin only)
- `DELETE /products/:id` - Delete product (admin only)

### Categories
- `GET /categories` - Get all categories
- `POST /categories` - Create category (admin only)
- `PUT /categories/:id` - Update category (admin only)
- `DELETE /categories/:id` - Delete category (admin only)

### Cart
- `GET /cart` - Get user cart (protected)
- `POST /cart` - Add item to cart (protected)
- `PUT /cart/:itemId` - Update cart item (protected)
- `DELETE /cart/:itemId` - Remove item from cart (protected)

### Orders
- `GET /orders` - Get user orders (protected)
- `POST /orders` - Create order (protected)
- `GET /orders/:id` - Get order details (protected)
- `PUT /orders/:id` - Update order status (admin only)

### Payments
- `POST /payments` - Process payment (protected)
- `GET /payments/:id` - Get payment details (protected)

## Response Format
All responses are in JSON format:
```json
{
  "success": true,
  "data": {},
  "message": "Operation successful"
}
```

## Error Response
```json
{
  "success": false,
  "error": "Error message"
}
```
