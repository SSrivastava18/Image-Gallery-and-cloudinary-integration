Image Gallery App:
An interactive image gallery application built with the MERN stack (MongoDB, Express.js, React, Node.js) and integrated with Cloudinary for seamless image uploads and storage.


Features:
  ->Drag & Drop image upload

  ->Cloudinary integration for image storage

  ->Image preview with filename

  ->Upload multiple files at once

  ->Images stored and served via MongoDB & Express API

  ->Automatic gallery refresh on new upload

  ->Filename includes timestamp for easy tracking

Tech Stack:
Layer	                  Technology
Frontend	              React (Create React App)
Backend	                Node.js, Express.js
Database	              MongoDB (Mongoose)
Image Upload	          Cloudinary API

Getting Started
 1. Clone the repo
     git clone https://github.com/SSrivastava18/Image-Gallery-and-cloudinary-integration.git
     cd image-gallery-app
 2. Setup Environment Variables
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     CLOUDINARY_CLOUD_NAME=your_cloud_name
     CLOUDINARY_API_KEY=your_api_key
     CLOUDINARY_API_SECRET=your_api_secret
3. Install Dependencies
   Backend:
     cd server
     npm install
   Frontend:
     cd ../client
     npm install
4. Run the App
Start backend:
  cd server
  npm start
Start frontend:
  cd ../client
  npm start





