# Mapping-Data-Components

# Mapping Components App

A React application that demonstrates mapping over data to dynamically render reusable components. This app displays a list of contact cards using React components and props.

## Table of Contents

1. [Overview](#overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Technologies](#technologies)
6. [Folder Structure](#folder-structure)
7. [Scripts](#scripts)
8. [License](#license)

## Overview

This project uses React to render a list of contacts with a reusable `Card` component. Each contact card displays information such as the name, profile image, phone number, and email address.

## Installation

### Prerequisites

- Node.js (version 12 or above)
- npm (version 6 or above)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/jbolan12/Mapping-Data-Components.git


**Navigate to the project directory:**

bash
cd your-repo

**Install the dependencies:**

bash
npm install

**Start the development server:**

bash
npm start
Open your browser and go to http://localhost:3000 to view the app.


## Usage
The application imports a contacts array containing contact data, which is mapped to generate Card components dynamically. Each Card displays:

- Name
- Profile image
- Phone number
- Email
- The createCard function maps over the contacts array, generating one Card component per contact. In addition, the app directly renders individual Card components as examples.

**Example**
In contacts.js:

javascript

const contacts = [
  {
    id: 1,
    name: "Beyonce",
    imgURL: "https://blackhistorywall.files.wordpress.com/2010/02/picture-device-independent-bitmap-119.jpg",
    phone: "+123 456 789",
    email: "b@beyonce.com"
  },
  {
    id: 2,
    name: "James Bond",
    imgURL: "https://hips.hearstapps.com/hmg-prod/images/casino-royale-james-bond-daniel-craig-1548342795.jpg?crop=0.566xw:1.00xh;0.332xw,0&resize=360:*",
    phone: "555 0123",
    email: "j.bond@MI6.com"
  }
];
export default contacts;


## Features
- Dynamic Rendering: Utilizes mapping to dynamically render components from data.
- Reusable Components: Implements a reusable Card component.


## Technologies
- React (v16.8.6)
- React DOM (v16.8.6)
- React Scripts (v3.2.0)
- CSS for styling in styles.css


## Scripts
The following scripts are available in the project:

- start: Runs the app in development mode with react-scripts start.
- build: Builds the app for production using react-scripts build.
- test: Runs the test suite with react-scripts test --env=jsdom.
- eject: Ejects the app from Create React App configuration.


## License
This project is licensed under the MIT License.
