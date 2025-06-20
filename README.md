# Local Services Booking Platform

A full-stack Java web application that connects customers with local service providers across categories such as home cleaning, beauty services, appliance repair, and more.

## Features

- Secure registration and login with role-based access (Admin, Customer, Vendor)
- Real-time service filtering using AJAX
- Admin dashboard to manage users, vendors, and bookings
- Multiple payment gateway integration via Razorpay (demo)
- Vendor availability and time slot management
- Email notifications for booking confirmations and schedule updates
- OTP-based password reset via email
- Customer payment history tracking
- Vendor management with full CRUD operations

## Technologies Used

- Backend: Java Servlets, MVC Architecture
- Frontend: JSP, HTML, CSS, JavaScript, AJAX
- Database: MySQL (created using SQLyog)
- Server: Apache Tomcat
- IDE: Eclipse

## Project Structure

├── controller/  Java servlets (business logic)
├── model/  DAO classes and database access
├── view/  JSP pages (user interface)
├── webapp/  Static files and web resources
├── db.properties  Database configuration file


## Setup Instructions

1. Clone the repository and import the project into Eclipse.
2. Configure Apache Tomcat as the runtime server.
3. Import the provided SQL file into MySQL using SQLyog or another MySQL client.
4. Update the database credentials in `db.properties`.
5. Run the project using Tomcat and open in your browser at `http://localhost:8080`.
