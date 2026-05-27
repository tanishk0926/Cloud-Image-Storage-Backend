# Image Upload Backend API

This is my first backend project built using Node.js, Express.js, MongoDB, Multer, and ImageKit.

## Features

- Upload image using Multer
- Store image on ImageKit
- Save post data in MongoDB
- Fetch all posts

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- Multer
- ImageKit

## Installation

```bash
npm install
```

## Run Server

```bash
npm start
```

## Environment Variables

Create a `.env` file and add:

```env
MONGODB_URI=
IMAGEKIT_PRIVATE_KEY=
```

## API Endpoints

### Create Post

```http
POST /create-post
```

### Get Posts

```http
GET /posts
```

## Author

Tanishk Sulaniya
