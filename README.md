
# Hostel-Hunt

Hostelhunt is a web application built using the MERN stack (MongoDB, Express.js, React, Node.js) that allows users to find hostels and hostel owners to list their properties.


## Features

 -- User Roles: User and Hostel Owner
 - Hostel Owner:
   - SignUp/Login
   - Create a hostel
   - Add detailed information about the hostel
 - User:
   - SignUp/Login
   - Set filters based on location
    - View detailed information about hostels


## Installation

To get a local copy up and running follow these simple steps.

Make sure you have the following installed:

 - Node.js
 - npm (Node Package Manager)
 - MongoDB

1. Clone the project/ Download zip file
```bash
  git clone https://github.com/yourusername/hostelhunt.git
  cd hostelhunt  
```
2. Install Dependencies
Navigate to both the server and client directories and install the dependencies:
```bash
cd server
npm install

cd ../client
npm install
```
3. Set up MONGO_URI in server->db.js
```bash
MONGO_URI=your_mongodb_connection_string
```
4. Run the Application
To run the application in development mode, open two terminal windows. In one, start the server:
```bash
cd server
npm run dev
```
```bash
cd client
npm start
```

The application should now be running on http://localhost:3000.


    
## Demo

 - Hostel Owner
   - Sign up and log in as a hostel owner.
   - Create a new hostel and add detailed information such as location, facilities, and pricing.
 - User
   - Sign up and log in as a user.
   - Use the filters to search for hostels based on location.
   - View detailed information about each hostel.

