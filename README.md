Inventory Management System for College Stationery Products (Flutter App)
Project Overview
This project is an Inventory Management System built as a Flutter mobile app to manage requisitions of stationery products by faculty members at a college. Faculties can request stationery items (like pens, notebooks, and other office supplies) through a requisition form. The app interacts with Firebase for real-time data storage, authentication, and notifications.

Admins can manage inventory, approve or reject faculty requisitions, and track stock levels directly through the app.

Features
Faculty Requisition Form: Faculty members can fill out a form to request stationary items (e.g., pens, notebooks, markers).
Inventory Management: Admins can manage inventory (add, update, or remove items).
Request Approval: Admins can approve or reject requisition requests based on available stock.
Real-Time Database: Firebase Firestore is used for real-time updates of the requisition requests and inventory.
Authentication: Firebase Authentication allows faculty members and admins to log in securely.
Push Notifications: Faculty members receive notifications about the status of their requisitions (approved/rejected).
Admin Dashboard: Admins can view all requisitions, current inventory, and generate reports for stock management.
Technologies Used
Flutter: For building a cross-platform mobile application for both iOS and Android.
Firebase:
Firebase Authentication for secure login and user management.
Firebase Firestore for real-time database to store requisitions, products, and inventory details.
Firebase Cloud Messaging (FCM) for push notifications.
Provider: State management for the app (optional).
Flutter Local Notifications: For in-app notifications.
System Requirements
Flutter SDK: To build the mobile application.
Android Studio or Visual Studio Code: For code editing and app development.
Firebase Project: Set up a Firebase project for authentication, Firestore, and notifications.
Device or Emulator: An Android or iOS device or emulator to run the app.
Installation Guide
Prerequisites
Install Flutter SDK:

Download and install the Flutter SDK from the official website: Flutter Installation Guide.
Install Android Studio or Visual Studio Code for development and running the app.

Set up a Firebase Project:

Create a Firebase project on the Firebase Console.
Enable Firebase Authentication and set up Firestore Database.
Add your Android and/or iOS app to the Firebase project.
