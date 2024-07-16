
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
## Screenshots
![1Homepage_login](https://github.com/user-attachments/assets/f10b87bf-435b-4904-a3e4-a1a3140d5358)

![4LoggedIn](https://github.com/user-attachments/assets/cf0ba9a1-68d7-445c-ba66-0da618121f02)

![6Filter](https://github.com/user-attachments/assets/97cc18f5-acb3-4b15-b950-87ccd8aa37e6)

![8HostelPage](https://github.com/user-attachments/assets/e8eac4e0-d74a-4b29-b04d-8219455e0d3c)
