# Airbnb Clone
Name: C S GOUTHAM REDDY
Project: Primetrade.ai
## Overview

This project is a full-stack web application developed as a clone of Airbnb using the MERN stack (MongoDB, Express.js, React.js, Node.js). It aims to replicate the core functionality of Airbnb, allowing users to search for accommodations, view details, make bookings, and manage their listings.

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/GouthamReddy20/airbnb.git

   ```

2. **Install dependencies:**

   Navigate to client directory and install frontend dependencies using yarn

   ```
   yarn install
   ```

   Similary navigate to api folder and install backend dependencies

   ```
   yarn install
   ```

3. **ENV variables:**

   - create .env file in the client folder and add these variables

     #### VITE_BASE_URL= http://localhost:4000

     #### VITE_GOOGLE_CLIENT_ID= your google client id

   - create .env file in the api folder and add these variables

     #### PORT= 4000

     #### DB_URL= your db url

     #### JWT_SECRET= your secret (string)

     #### JWT_EXPIRY= 20d

     #### COOKIE_TIME= 7

     #### SESSION_SECRET= your secret session (string)

     #### CLOUDINARY_NAME= your secret session

     #### CLOUDINARY_API_KEY= your cloudinary key

     #### CLOUDINARY_API_SECRET= your cloudinary api secret

     #### CLIENT_URL= http://localhost:5173

4. **Run project:**
   - Open terminal, navigate to client directory and run below command to start frontend
   ```
       yarn run dev
       or
       npm run dev
   ```
   - Open another terminal, navigate to api directory and run this command to start backend server
   ```
       yarn start
       or
       npm start
   ```

## Features

- **User Authentication:** Users can sign up, log in, and log out securely. Passwords are hashed for security.
- **Google Login:** Users can sign up and log in using their gmail.

  ![Airbnb Logo](client/public/assets/a<img width="1920" height="1080" alt="auth" src="https://github.com/user-attachments/assets/65561811-5c1b-4947-adec-79f539ba166d" />
uth.png)

- **Search Listings:** Users can search for accommodations.

  ![Airbnb Logo](client/public/assets/s<img width="2560" height="1121" alt="search" src="https://github.com/user-attachments/assets/903276f6-7325-4c72-891b-ecf0e2d98684" />
earch.png)

- **View Listings:** Users can view detailed information about each accommodation, including photos, descriptions, amenities.

  ![Airbnb Logo](client/public/a<img width="2560" height="1369" alt="view" src="https://github.com/user-attachments/assets/25da285f-d2da-48ef-979f-a08d1d0c3a47" />
ssets/view.png)

- **Make Bookings:** Authenticated users can book accommodations for specific dates.

  ![Airbnb Logo](client/public/assets/book.<img width="1977" height="1112" alt="book" src="https://github.com/user-attachments/assets/753e9c82-4ff1-4242-bb57-0cccb1bb25e0" />
png)

- **Manage Listings:** Hosts can create, edit, and delete their listings.

  ![Airbnb Logo](client/public/assets/manage<img width="2560" height="1214" alt="manage" src="https://github.com/user-attachments/assets/916b3976-bc48-440a-95c1-33b8a207bb30" />
.png)

- **Responsive Design:** The application is designed to be responsive and work seamlessly across different devices.

  ![Airbnb Logo](client/public/assets<img width="1851" height="1111" alt="hero" src="https://github.com/user-attachments/assets/78e8ed3d-d7cc-4568-9bae-f67a849d5494" />
/hero.png)

## Technologies Used

- **MongoDB:** NoSQL database for storing user data, listings.
- **Express.js:** Web application framework for building the backend server.
- **React.js:** JavaScript library for building the user interface.
- **Node.js:** JavaScript runtime environment for executing server-side code.
- **Tailwind CSS:** A utility-first CSS framework
- **Shadcn:** UI library for styling based on Tailwind CSS
- **JWT:** JSON Web Tokens for secure user authentication.
- **Cloudinary:** Cloud-based image management for storing and serving images.
- **Google Cloud:** For gmail based authentication
# airbnb
# airbnb
