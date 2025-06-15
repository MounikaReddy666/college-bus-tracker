College Bus Tracker
A web-based application to track college buses in real-time, enabling students to select pickup stops, view live bus locations, and check pickup statuses at GITAM University.
Project Overview
This app addresses the communication gap between hostel students and bus drivers during weekend outings at GITAM University. Students can track the bus live, select their pickup stop, and see when they’ve been picked up, reducing calls and improving efficiency. Drivers can share their real-time location and confirm student pickups.
Features

Student Role:
Secure login/register with email and password.
Select pickup stop from a dropdown list.
View live bus location on Google Maps.
See pickup status (red for waiting, green for picked up).


Driver Role:
Secure login.
Share real-time GPS location.
Confirm student pickups manually.



Tech Stack

Frontend: HTML, CSS, JavaScript
Backend: Firebase Realtime Database, Firebase Functions
Authentication: Firebase Authentication (Email/Password)
Map Services: Google Maps JavaScript API
Hosting: Firebase Hosting
IDE: Visual Studio Code
Version Control: Git, GitHub

Current Progress

Week 1 (as of June 15, 2025):
Planned features for student and driver roles.
Set up Firebase project "CollegeBusTracker" with:
Web app "bus-tracker-app" registered.
Email/Password Authentication enabled.
Realtime Database enabled in test mode.


Initialized project folder with boilerplate files (index.html, style.css, script.js, firebase-config.js, .gitignore, README.md).
Created GitHub repository: https://github.com/MounikaReddy666/college-bus-tracker.



Setup Instructions

Clone the Repository:git clone https://github.com/MounikaReddy666/college-bus-tracker.git
cd college-bus-tracker


Add Firebase Config:
Create a firebase-config.js file in the project root.
Paste your Firebase configuration (obtain from Firebase Console).
Example format:const firebaseConfig = {
  apiKey: "your-api-key",
  authDomain: "your-project-id.firebaseapp.com",
  databaseURL: "https://your-project-id-default-rtdb.firebaseio.com",
  projectId: "your-project-id",
  storageBucket: "your-project-id.appspot.com",
  messagingSenderId: "your-sender-id",
  appId: "your-app-id"
};
firebase.initializeApp(firebaseConfig);
const db = firebase.database();
const auth = firebase.auth();




Run Locally:
Install the Live Server extension in VS Code.
Right-click index.html and select Open with Live Server to preview the app.


Install Firebase CLI (for deployment later):npm install -g firebase-tools
firebase login



Next Steps

Week 2:
Design UI wireframes for Login, Student Dashboard, and Driver Dashboard.
Implement Firebase Authentication for login/register.
Set up basic HTML/CSS for the login page.


Future Weeks:
Integrate Google Maps API for live bus tracking.
Develop Realtime Database structure for stops, locations, and pickup statuses.
Build student and driver dashboards.
Deploy to Firebase Hosting.



Demo
(To be added after deployment)
Contributing
This is a personal project for my internship at GITAM University. Contributions are not open at this time, but feedback is welcome via GitHub Issues.
License
(To be determined upon completion)
