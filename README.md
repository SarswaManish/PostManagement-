# PostManagement-
# Fire up MongoDB container
docker run -d -p 27017:27017 --restart unless-stopped --name commentsmongo mongo

# Fire up Redis container
docker run -d -p 6379:6379 --restart unless-stopped --name commentsredis redis

# Go into the backend directory
cd comment-system/backend

# Install dependencies
npm install

# Start the server
npm start

# Go into main app directory
cd ..

# Install dependencies
npm install

# Start the App
npm start

```

## Features

- [x] Realtime comments & upvotes/downvotes using **WebSockets** & **Redis**

- [x] **JWT** based authorization

- [x] Microservice architecture using **Node.js** & **Express**

- [x] Caching in **Redis** & Persistent Storage in **MongoDB** using **Mongoose ODM**

- [x] Container based development using **Docker**


## Technology Stack

- Node.js
- React
- MongoDB
- Redis
- WebSockets
- JWT
