# Twitter Clone - Vanilla JavaScript with OOP

This is a simple front-end clone of Twitter, built with modern JavaScript (vanilla) and Object-Oriented Programming (OOP) principles. The project includes functionalities like user registration, login, posting tweets, and managing user profiles, with data persistence via local storage. Tailwind CSS is used for responsive and clean design.

## Features
- User registration and login.
- Post, manage, and display tweets.
- User profile management.
- Local storage for data persistence across sessions.
- Tailwind CSS for a clean, responsive UI.
- Object-Oriented Programming (OOP) to structure code for scalability.

## Technologies Used
- **Vanilla JavaScript (OOP)**
- **HTML5**
- **Tailwind CSS**
- **Local Storage**

## Installation

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/username/twitter-clone-vanilla-js.git
2. cd twitter-clone-vanilla-js
3. open index.html

##Usage
1. Open the index.html page in your browser.
2. Register a new user through register.html.
3. Log in using login.html.
4. Post new tweets, which will be stored in local storage.
5. View and manage your profile in profile.html.

##Project Structure
twitter-clone-vanilla-js/
│
├── assets/
│   ├── css/
│   │   └── tailwind.css      # Tailwind CSS file
│   └── js/
│       ├── addTwitt.js       # Logic to add new tweets
│       ├── addUser.js        # Logic to add new users
│       ├── manageTwitts.js   # Logic to manage tweet data
│       ├── Twitt.js          # Twitt class for tweet objects (OOP)
│       ├── User.js           # User class for user objects (OOP)
│       ├── userProfile.js    # Logic to handle user profile data
│       ├── userSignin.js     # Logic to handle user login
│
├── index.html                # Homepage
├── login.html                # Login page
├── register.html             # Register page
├── profile.html              # Profile page
├── README.md                 # Project documentation
└── .gitignore                # Ignore unnecessary files
