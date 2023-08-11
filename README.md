# StoryTellingApp

A web application built with Node.js, Express, MongoDB, and Google OAuth that enables users to create and share their own stories publicly or privately.

## Table of Contents
1. [StoryTellingApp](#storytellingapp)
2. [About](#about)
3. [Features](#features)
4. [Getting Started](#getting-started)
   1. [Prerequisites](#prerequisites)
   2. [Installation](#installation)
6. [Usage](#usage)
7. [Features](#features-1)
8. [Technologies Used](#technologies-used)
9. [Contact](#contact)


## About

The StoryTellingApp is a platform where users can create and share their stories with others. Users can log in using their Google accounts, create new stories, and view stories shared by other users. The app offers a simple and intuitive interface for storytelling.

## Features

- User authentication using Google OAuth
- Create new stories
- View and read stories
- Edit and update your stories
- Delete stories
- User dashboard with personalized content
- Responsive design for different devices

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB database
- Google OAuth API credentials

### Installation

1. Clone the repository:

```bash
git clone https://github.com/dancarlton/StoryTellingApp.git
```
2. Install dependencies:

```bash
cd StoryTellingApp
npm install
```
3. Configure Environment Variables:
```
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
MONGO_URI=your-mongodb-connection-uri
```
4. Start the Server with
```bash
npm start
```
or
```
nodemon app.js
```

## Usage

1. Navigate to `.env` file in the config folder and provide your own environment variables (such as MongoDB connection URI and Google OAuth credentials).
2. Run the development server: `npm run dev`
3. Open your web browser and go to: `http://localhost:3000`

## Features

- User authentication using Google OAuth
- Create, edit, and delete stories
- User-specific dashboard to manage stories
- Share stories with other users

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Passport.js (Google OAuth)
- Handlebars (templating engine)
- HTML, CSS (Styling)
- JavaScript (Front-end and Back-end)

## Contact

For inquiries or feedback, feel free to contact me at danc@dancarlton.com. You can also visit my [GitHub profile](https://github.com/dancarlton) for more projects.
