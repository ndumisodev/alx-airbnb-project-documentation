# 🧩 Use Case Diagram – Airbnb Clone Backend

This document provides a visual representation of the system's primary interactions for the **Airbnb Clone Backend**. It highlights how users (guests, hosts, admins) and external services interact with the system to perform key operations like registration, property listing, booking, payments, and notifications.

## ✅ Objective

To illustrate and document the core functionalities of the backend system through a **Use Case Diagram**, clearly outlining:

- Key actors (users and external systems)
- System use cases (functionalities)
- Interactions between actors and the system

## 📌 Features Represented

The diagram captures the following key backend functionalities:

- **User Management**: Registration, Login, Profile Management
- **Property Management**: Listing, Editing, and Deleting Properties (host role)
- **Booking Management**: Searching, Booking, Viewing, and Cancelling
- **Payment Integration**: Secure checkout using payment gateways
- **Notifications**: Email alerts for bookings, payments, and cancellations
- **Admin Control**: User and booking monitoring
- **System Logging**: Activity monitoring through an audit/logger service

## 👥 Actors

- **Guest** – Unregistered user searching and registering
- **Registered User** – Authenticated user who can book properties
- **Host (Registered User)** – Can list and manage properties
- **Admin** – Manages users and oversees bookings
- **Authentication Service** – Handles login and session control
- **Availability Checker / Pricing Engine** – Verifies booking availability and price
- **Payment Gateway** – Processes transactions securely
- **Email Notification Service** – Sends booking/payment emails
- **Audit Service / System Logger** – Tracks system events for audit purposes

## 🖼️ Diagram

![Use Case Diagram](./backend-alx-booking-uc.png)


## 📁 Directory Structure

