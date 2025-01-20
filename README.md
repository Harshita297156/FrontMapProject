FrontMapProject

Frontend Case Study Solution - Bynry Task

This repository contains the solution for the frontend case study provided by Bynry. The task was to create a web application using the React framework to display user profiles, provide interactive mapping, and manage profile data efficiently.

Although the project includes most of the requested functionalities, due to time constraints, the integration of the Google Maps service could not be implemented. The rest of the features were designed and implemented to the best of my ability to ensure a functional and user-friendly application.

Features Implemented


Profile Display

A dynamic webpage that presents a collection of user profiles.
Each profile includes essential information such as name, photograph, and a brief description.


Admin Panel

Administrators can add, edit, and delete profiles through an intuitive admin dashboard.
Provides seamless profile data management.


Search and Filter

Users can search and filter profiles based on attributes such as name and location, enhancing usability.


Profile Details View

Clicking on a profile reveals detailed information, including contact details and other relevant attributes.


Responsive Design

The application is fully responsive and mobile-friendly, offering a smooth experience on devices of all sizes.


Error Handling

Robust error handling mechanisms are in place for invalid inputs and system errors.


Loading Indicators

Loading indicators provide real-time feedback to users while fetching data or rendering components.


Code Quality

The project emphasizes clean and modular code for better readability and scalability.


Unfinished Features
The integration of Google Maps or any external map service for address visualization remains incomplete. However, placeholders and a structured approach are present, making future integration straightforward.


Technology Stack
Framework: React.js
Styling: CSS Modules and Material-UI
State Management: React Context API
Routing: React Router
Data Handling: JSON and local storage


Environment Setup

Note: The .env file containing environment variables must be placed in the public folder to ensure proper access during runtime.


Installation and Usage
To run the project locally:

Clone this repository:
git clone https://github.com/your-username/FrontMapProject.git


Navigate to the project directory:

cd FrontMapProject


Install dependencies:

npm install


Start the development server:

npm start
Open your browser and visit http://localhost:3000.


Future Enhancements

If given the opportunity, I plan to:

Implement Google Maps or Mapbox for interactive address visualization.
Optimize the performance of data fetching and state management.
Add unit and integration tests to ensure reliability.


Contact
Feel free to reach out for any questions or feedback:

Name: Harshita Sharma
Email: sharmaharshita636@gmail.com
LinkedIn: https://www.linkedin.com/in/harshita-sharma-64371a273/



# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
