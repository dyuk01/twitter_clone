# Twitter Backend Application

This project is a Twitter backend application built using Node.js, Prisma, SQLite, JWT authentication, passwordless authentication, various middlewares, user management functionalities, and Docker containerization.

## Features

- **User Authentication**: Secure sign-up and login functionality.
- **Tweet Functionality**: Users can compose, edit, and delete tweets.
- **Follow System**: Ability to follow and unfollow other users.
- **Timeline**: View tweets from followed users in a chronological feed.
- **Profile Pages**: Personalized user profiles displaying user information and tweets.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: Passport.js

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/dyuk01/twitter_clone.git
   cd twitter_clone
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Configure Environment Variables**:  
   Create a `.env` file in the root directory and add the following:
   ```
   PORT=3000
   MONGODB_URI=your_mongodb_uri
   SESSION_SECRET=your_session_secret
   ```

4. **Start the Application**:
   ```bash
   npm start
   ```
   The application will run on `http://localhost:3000`.

## Usage

- **Sign Up**: Create a new account using a valid email address.
- **Log In**: Access your account with your credentials.
- **Compose a Tweet**: Share your thoughts by posting a new tweet.
- **Follow Users**: Discover and follow other users to see their tweets in your timeline.
- **Edit Profile**: Update your personal information and profile picture
   ```



