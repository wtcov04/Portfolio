# Year 1: Draw App

## Overview
The Draw App is a simple web-based drawing application that allows users to create and edit drawings using various tools. Users can use tools such as pencil, spray can, eraser, and others to draw on a blank canvas or import images for editing. This app is built using HTML, JavaScript, and CSS.

## Features
- **Various Drawing Tools**: Includes tools like pencil, spray can, eraser, square tool, and more.
- **Colour Palette**: Allows the user to select colors for drawing.
- **Canvas Manipulation**: Users can draw freehand, add images, and manipulate shapes on the canvas.

## Technologies Used
- **HTML**: For the structure of the web page.
- **CSS**: For styling the app.
- **JavaScript**: To implement the drawing functionality and interactions.

## Key Files
- **index.html**: The main HTML file that sets up the app’s interface.
- **style.css**: Contains the CSS styling for the app.
- **JavaScript Files**: Each drawing tool and helper function is stored in separate `.js` files (e.g., `colourPalette.js`, `freehandTool.js`, `eraserTool.js`).

## Running the Project
1. Download or clone the repository to your local machine.
2. Open the `index.html` file in your web browser to launch the app.
3. Use the drawing tools available on the left side of the screen.

## Challenges & Solutions
- **Tool Interaction**: Initially, handling the interaction between different drawing tools was challenging. We solved this by using JavaScript event listeners to switch between tools dynamically.
- **Canvas Resize**: Handling resizing of the canvas dynamically without losing the user's work was another issue. We implemented a function to adjust the canvas size while maintaining the drawn content.

## Future Enhancements
- Adding more advanced drawing tools such as gradients or a line tool.
- Implementing a save feature to download drawings as images.
  

# Year 2: Event Planner

## Overview
The Event Planner app is a web-based application that helps users organize events, track schedules, and manage tasks. Users can create events, add tasks, and manage their event-related details. It includes authentication using Passport.js to ensure that only registered users can access their event data.

## Features
- **Event Creation**: Users can create events with detailed information (e.g., event name, date, time, description).
- **Task Management**: Users can add tasks to events, assign deadlines, and mark tasks as completed.
- **Authentication**: Passport.js is used to allow users to sign up, log in, and manage their events securely.
- **Database Integration**: Event data is stored in a relational database, created using `create_db.sql`.

## Technologies Used
- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Web framework for building the app.
- **Passport.js**: Authentication middleware for user login and registration.
- **SQL**: Used to store event and user data in a relational database.

## Key Files
- **index.js**: The main entry point for the app, setting up the server and routes.
- **create_db.sql**: SQL script to set up the database.
- **.env**: Contains environment variables like database credentials.
- **passport/**: Contains Passport.js strategy files for user authentication.
- **routes/**: Contains route handlers for different parts of the app (event management, user authentication, etc.).
- **public/**: Holds static files like images, CSS, and client-side JavaScript.
- **views/**: Contains EJS templates for rendering dynamic content on the frontend.

## Running the Project
1. Download or clone the repository to your local machine.
2. Install the required dependencies by running:
   ```bash
   npm install
