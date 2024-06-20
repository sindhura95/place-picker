# PlacePicker App

## Overview
PlacePicker is a React application designed to help users manage and select places they want to visit or have visited. It utilizes geolocation to sort available places by distance from the user's current location and allows users to create a personalized collection of selected places.

## Getting Started
To run the application locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Install dependencies by running `npm install`.
4. Start the development server with `npm run dev`.
5. Open your browser and visit `http://localhost:5173` to view the application.

## Features
1. Geolocation Sorting: Automatically sorts available places based on the user's current location using the navigator.geolocation API and custom distance calculation.
2. Persistent Storage: Utilizes localStorage to persist selected places across sessions.
3. Modal and Confirmation: Implements a reusable modal component with a delete confirmation that includes a countdown progress bar.
4. Dynamic Rendering: Renders lists of places with images and interactive buttons for selecting and removing places.

## Technologies Used
1. React
2. ReactDOM
3. JavaScript
4. HTML
