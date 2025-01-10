mongo_api_project/
├── src/
│   ├── config/
│   │   └── db.js          # MongoDB connection setup
│   ├── controllers/
│   │   └── itemController.js  # Logic for CRUD operations
│   ├── models/
│   │   └── itemModel.js   # Mongoose schema and model
│   ├── routes/
│   │   └── itemRoutes.js  # API routes
│   ├── app.js             # Express app configuration
├── .env                   # Environment variables
├── server.js              # Main server entry point
├── package.json           # Project metadata and dependencies

Use Thunder Client or Postman to test the endpoints:

POST /api/items with body: { "name": "Apple", "quantity": 5 }
GET /api/items
PUT /api/items/:id with body: { "name": "Orange", "quantity": 10 }
DELETE /api/items/:id
Set up Postman environment variables for easy testing:

base_url = http://localhost:5000/api/items.
