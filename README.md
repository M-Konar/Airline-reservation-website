# Zeyad Tyara Air Travel Agency Website

Welcome to the Zeyad Tyara Air Travel Agency website, dedicated to those who love traveling and adventure!

## Features

- View and book flights: As a user, you can explore all available flights using search filters to find the one that suits you best. You have the convenience of booking your flights online.
- Flight management (Admin): As an admin, you have full control over flight management. You can create new flights, view existing flights with search filters, and easily edit or delete flights using the intuitive interface.
- Real-time updates: Any changes made by the admin are instantly reflected on the backend and the database.
- Technology stack: The website is built using the MERN stack (MongoDB, Express, React, Node.js), ensuring a robust and efficient development experience. The database is hosted on the cloud using the MongoDB free plan.

## Motivation

This project was created as part of the Advanced Computer Lab course. While our primary motivation may have been the grades (who doesn't love good grades?), we also had a lot of fun and utilized the opportunity to test our self-learning and programming skills as aspiring computer engineers.

## Build Status

The project is functioning flawlessly without any errors or bugs.

## Code Style

The project is divided into two parts: the client-side (frontend) and the server-side (backend). We have followed the Model-View-Controller (MVC) architecture in the backend, organizing each category of users (Admin, Guest, User) into separate folders within the project structure. On the client-side, components are modularized, with each component representing a specific frontend functionality that maps to the backend.

## Screenshots


<p align="center">Login Portal</p>

<p align="center">
  <img src="https://github.com/m-abdelgaber/Airline-reservation-website/assets/85055466/754492bd-7cf5-46f5-89f3-9c5eb4c4edc4" alt="Login Portal" width="400">
</p>

<br><p align="center">Signup Portal</p>

<p align="center">
  <img src="https://github.com/m-abdelgaber/Airline-reservation-website/assets/85055466/19ae84d5-827a-4e60-afca-a737bf1f3c0e" alt="Signup Portal" width="400">
</p>

<br><p align="center">Creating a New Flight (exclusive for admins only)</p>

<p align="center">
  <img src="https://github.com/m-abdelgaber/Airline-reservation-website/assets/85055466/ea5ec124-49b4-4efb-b1e2-38eed064f73a" alt="Creating a New Flight" width="400">
</p>


<br><p align="center">Editing or Deleting an Existing Flight (exclusive for admins only)</p>

<p align="center">
  <img src="https://github.com/m-abdelgaber/Airline-reservation-website/assets/85055466/34c0f69d-b5ee-4d12-9e58-afcbb931a545" alt="Editing or Deleting an Existing Flight 1" width="400">
</p>

<p align="center">
  <img src="https://github.com/m-abdelgaber/Airline-reservation-website/assets/85055466/5073d191-c5b2-4fb9-a307-923dc43b487e" alt="Editing or Deleting an Existing Flight 2" width="400">
</p>


<br><p align="center">Reserving a Flight (Users)</p>

<p align="center">
  <img src="https://github.com/m-abdelgaber/Airline-reservation-website/assets/85055466/69720b76-5bde-4cca-a009-3c9b8b558948" alt="Reserving a Flight 1">
</p>

<p align="center">
  <img src="https://github.com/m-abdelgaber/Airline-reservation-website/assets/85055466/26f27744-9b92-4417-af2e-2b6e79911d51" alt="Reserving a Flight 2">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/82762206/147392654-d3466269-5b30-4d79-942e-ddcf0d5f2d08.png" alt="Reserving a Flight 3">
</p>


<br><p align="center">Payment for Reservation (Users)</p>

<p align="center">
  <img src="https://github.com/m-abdelgaber/Airline-reservation-website/assets/85055466/f76db51d-3b34-4e9c-88ad-62aab361792e" alt="Payment for Reservation 1" >
</p>

<p align="center">
  <img src="https://github.com/m-abdelgaber/Airline-reservation-website/assets/85055466/ab56f3cf-ce02-40fd-87c0-e42c2fadd150" alt="Payment for Reservation 2" >
</p>

<br><p align="center">Updating Personal Information (Users)</p>

<p align="center">
  <img src="https://github.com/m-abdelgaber/Airline-reservation-website/assets/85055466/0757ae73-57bc-4f7d-8577-38a1d03dfb55" alt="Updating Personal Information" width="400">
</p>


<br><p align="center">View/Cancel/Edit My Reservations (Users)</p>

<p align="center">
  <img src="https://github.com/m-abdelgaber/Airline-reservation-website/assets/85055466/a7087136-6198-4d89-8d97-6ccb1c7dfaba" alt="View/Cancel/Edit My Reservations" width="400">
</p>


<br><p align="center">Edit Reservation (Users)</p>

<p align="center">
  <img src="https://github.com/m-abdelgaber/Airline-reservation-website/assets/85055466/8135b1cb-425f-4468-9711-6fa86e9a6d35" alt="Edit Reservation" width="400">
</p>


## Tech/Framework Used

The Zeyad Tyara Air Travel Agency website is built using the following technologies and frameworks:
- MongoDB
- Express.js
- React.js
- Node.js (MERN Stack)

## Installation

To install and run the project, follow these steps:

1. Install npm:
```
npm install
```
2. Install the Express module:
```
npm i express
```
3. Install the CORS module:
```
npm i cors
```
4. Install the Bcrypt module:
```
npm i bcrypt
```
5. Install Stripe:
```
npm i stripe
```

## API Reference

To integrate with external services, we have used the following API references:
- [Nodemailer](https://nodemailer.com/about/)
- [Stripe API Authentication](https://stripe.com/docs/api/authentication)
- [Unsplash API Documentation](https://unsplash.com/documentation)

## Tests

For testing backend functions before integrating them with the frontend, we recommend using the Postman application. You can download it from [here](https://www.postman.com/downloads/). Additionally, you can utilize Chrome Developer Tools for testing and debugging purposes.

## How to Use

The project consists of two parts: the frontend and the backend. Both parts need to be running to experience the full functionality of the flight reservation system.

To run the backend:

1. Open the console.
2. Change the directory to `Server`:
```
cd Server
```
3. Start the backend server:
```
node index
```

To run the frontend:

1. Open a new terminal.
2. Change the directory to `Client`:
```
cd Client
```
3. Start the frontend:
```
npm start
```

Your default browser will load the website, and you can navigate through it normally. If you want to log in as an admin, you need to manually enter the route `/adminLogin`.

## Contribute

We welcome contributions and feedback from the community. Feel free to share your thoughts and suggestions by sending an email to airlineszeyad@gmail.com. Together, we can make the Zeyad Tyara Air Travel Agency website even better!
