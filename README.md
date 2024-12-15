# Eventicity - Campus Event Management System

## Project Overview
A comprehensive web-based event management system designed for campus environments. The platform enables students and staff to view and register for various campus events including workshops, seminars, sports events, and club activities. Administrators can create and manage events while users can set preferences and RSVP to events of interest.

## Features ✅

### User Features
- User Authentication (Register/Login)
- Event Viewing and RSVP
- Event Preference Settings
- Calendar View of Events
- Event Filtering by Type

### Admin Features
- Event Creation and Management
- Dashboard with Statistics
- Recent Activity Monitoring
- Event Deletion

## Login Credentials

### Admin Access
- Email: admin@example.com
- Password: admin123

### Test User Access
- Email: user@example.com
- Password: user123

## API Documentation

### 1. User Authentication Endpoints

#### Register User
- **Endpoint**: POST `/api/users/register`
- **Description**: Creates new user account
![Screenshot 2024-12-14 at 9 48 51 PM](https://github.com/user-attachments/assets/f33d37af-f1a5-44da-a254-974a2093ceef)


#### Login User
- **Endpoint**: POST `/api/users/login`
- **Description**: Authenticates user and returns JWT token
![Screenshot 2024-12-14 at 9 49 49 PM](https://github.com/user-attachments/assets/03a456b6-9d78-4352-bb84-f8658afe7ad2)

### 2. Event Endpoints

#### Get All Events
- **Endpoint**: GET `/api/events`
- **Description**: Retrieves list of all events
![Screenshot 2024-12-14 at 9 54 22 PM](https://github.com/user-attachments/assets/613447f0-ef94-4ea8-a98e-92085a7ebb66)
![Screenshot 2024-12-14 at 9 54 45 PM](https://github.com/user-attachments/assets/c20bd5b7-86b4-4a1b-836e-5d97ea221191)



#### Create Event (Admin only)
- **Endpoint**: POST `/api/events`
- **Description**: Creates a new event
![Screenshot 2024-12-14 at 10 01 21 PM](https://github.com/user-attachments/assets/079c35be-5224-428d-b44c-766066fb3716)


#### Delete Event (Admin Only)
- **Endpoint**: POST `/api/events/:id/rsvp`
- **Description**: Delete event
  ![Screenshot 2024-12-14 at 10 05 16 PM](https://github.com/user-attachments/assets/373aa4be-c701-45e2-a839-b1303ed475c4)


### RSVP to Event
- **Endpoint**: POST `/api/events/:id/rsvp`
- **Description**: Registers user for an event
![Screenshot 2024-12-14 at 10 01 21 PM](https://github.com/user-attachments/assets/57480dec-281d-4a64-89ad-90a5d92e15e5)



### 3. Admin Endpoints

#### Get Dashboard Statistics
- **Endpoint**: GET `/api/admin/dashboard`
- **Description**: Returns overview of system statistics
![Screenshot 2024-12-14 at 10 14 21 PM](https://github.com/user-attachments/assets/ff5c52ee-8341-4a01-8732-36fc7a020ebf)


#### Get Recent Activity
- **Endpoint**: GET `/api/admin/activity`
- **Description**: Returns recent events and user registrations
![Screenshot 2024-12-14 at 10 14 59 PM](https://github.com/user-attachments/assets/91b46ebb-7816-494a-aa3e-fe7f8c68221b)
![Screenshot 2024-12-14 at 10 15 07 PM](https://github.com/user-attachments/assets/0ab2c2e4-208b-4af8-b073-e5b7012ec2dd)


#### Create Admin
- **Endpoint**: POST `/api/admin/create`
- **Description**: Creates a new admin user
![Screenshot 2024-12-14 at 10 21 06 PM](https://github.com/user-attachments/assets/078ca8fe-dac0-4d9b-8adb-6e7d38a5f871)




## Technologies Used
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT



## Installation Instructions
To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/GyameraYaw/Eventicity.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd Eventicity
    ```

3. **Install dependencies:**
    ```bash
    npm install
    ```
    
4. **Start the server:**
    ```bash
    npm start
    ```

Your backend should now be running on `http://localhost:5000` (or the port you've configured).



## Deployment Link
You can view the deployed frontend here:

Frontend: [Eventicity Frontend](https://eventicity-frontend.onrender.com)

