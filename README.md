# Contact Management System

This project is a contact management system developed using the MERN stack (MongoDB, Express.js, React, and Node.js). It provides functionality to view, manage, and download contacts, as well as add new contacts via a web form.

## Features

- **View Contacts**: Display contacts with pagination support.
- **Manage Contacts**: Add new contacts through a user-friendly web interface.
- **Download Contacts**: Download selected contacts in Excel format.

## Prerequisites

Before you begin, ensure you have the following requirements installed:
- **Node.js and npm**: Download and install from [Node.js official website](https://nodejs.org/).
- **MongoDB**: Set up locally or use a cloud instance. Follow instructions on [MongoDB's official site](https://www.mongodb.com/try/download/community).

## Installation

Follow these steps to set up the project locally.

### 1. Clone the repository

Clone the project repository by running:
git clone https://github.com/your-username/your-project-name.git
cd your-project-name


### 2. Setup Backend

Navigate to the backend directory:
cd backend

Install the required packages:
npm install

Create a `.env` file in the root of the backend directory and update it with your MongoDB URI and any other environment-specific configurations:
MONGODB_URI="Make sure to add your own URI"
PORT=5000


### 3. Setup Frontend

Navigate back to the project root, then to the frontend directory:
cd ../frontend
Install the required packages:
npm install


### 4. Run the Application

#### Start the Backend
Make sure you are in the backend directory, then start the server:
npm start
This will launch the Node.js server on `http://localhost:5000`.

#### Start the Frontend
Open a new terminal window, navigate to the frontend directory, and run:
npm start
This command will start the React application on `http://localhost:3000`.
Note: "/create" route in the client can be used to create a new entry for a contact.

## Usage
After starting both servers, open a web browser and visit `http://localhost:3000` to interact with the application. You can view, add, or download contacts from the UI.

