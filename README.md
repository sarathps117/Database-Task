# Database Task - Assignment 13

## Overview
This project is a REST API built using **ExpressJS + Mongoose** to manage posts in a MongoDB database.

## Setup
1. Clone this repository.
2. Install dependencies:
```bash
npm install
```
3. Set MongoDB URI (optional, default is local):
```bash
export MONGO_URI='your-mongodb-uri'
```
4. Start the server:
```bash
npm start
```
Server runs on **port 3000**.

## Endpoints
- `GET /getPosts` → Get all posts.
- `POST /addPosts` → Add a new post.
  - Body JSON: `{ "title": "Sample Title", "content": "Some content" }`
- `DELETE /delPosts/:id` → Delete a post by ID.
- `PATCH /post/:id` → Update a post by ID.

## Notes
- MongoDB connection required for full functionality.
- Includes a Postman collection for testing.

## Submission
- Push to GitHub with screenshots showing API usage and DB changes.
