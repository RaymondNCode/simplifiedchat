![alt text](simplified-chat-logo-nobg.png)
# simplified chat

A real-time chat application built using Firebase Authentication and Firestore.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)

## Introduction

Simplified chat is a real-time chat application that leverages Firebase Authentication for user management and Firebase Firestore for data storage. Users can sign in with their Google Account to log in.

## Features

- User Authentication (direct sign in with google)
- Real-time messaging
- User presence status
- Responsive UI

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/chatapp.git
   cd chatapp

2. Install dependencies:
   ```sh
   npm install

3. Install Firebase:
   ```sh
   npm install firebase

## Configuration
Firebase Setup
1. Create a Firebase Project:
- Go to the Firebase Console.
- Click on "Add Project" and follow the instructions to create a new Firebase project.

2. Enable Firebase Authentication:
- In the Firebase Console, select your project.
- Navigate to the "Authentication" section.
- Click on the "Sign-in method" tab.
- Enable the "Google" sign-in provider and configure it with the required information.
  
3. Set Up Firestore:
- In the Firebase Console, select your project.
- Navigate to the "Firestore Database" section.
- Click on "Create database" and follow the instructions to set up Firestore in production mode   or test mode.

4. Add Firebase Configuration to Your Project:
- Add a web app to your Firebase project to get your Firebase configuration details.
- replace all the below information with in 'firebaseConfig.js' with your own Firebase    
  configuration.
```sh
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
