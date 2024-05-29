Netlify Link :-https://prakhar-jain.netlify.app/


#APP FEATURES AND FUNCTIONS:-

TMDB API Integration: Utilizes the TMDB (The Movie Database) API for fetching movie data.

Featured Movie List: Displays a featured list of movies on the main page sourced from the TMDB API.

Search Functionality: Implements a search feature allowing users to search for movies by title.

Movie Details: Fetches detailed information about selected movies from the TMDB API, including overview, release date, rating, and poster image.

User Authentication: Provides user authentication functionalities like login, registration, and logout.

Protected Routes: Implements private routes that require user authentication to access certain pages, such as movie details.

Context API: Utilizes the Context API for managing user authentication state across components.

React Router: Uses React Router for client-side routing and navigation between different pages of the application.

Bootstrap Integration: Incorporates Bootstrap for styling components and enhancing the overall UI/UX.

Toast Notifications: Utilizes toast notifications for displaying user-friendly messages, such as login prompts or error alerts.





#TO RUN THIS PROJECT IN YOUR DEVICE:-

Clone the Repository: Start by cloning the project repository from the version control system (e.g., GitHub) to your local machine.

Install Dependencies: Navigate to the project directory using the command line interface and run npm install to install all project dependencies listed in the package.json file.

Environment Variables: Create a .env file in the project root directory to store sensitive information like API keys. In this case, you'll need to add the TMDB API key as REACT_APP_TMDB_KEY=your_api_key.

Start the Development Server: Run npm start to start the development server. This command will compile the React code and launch the application in your default web browser.

Register/Login: If the application includes user authentication, navigate to the registration or login page and create a new account or log in with existing credentials.

Explore Featured Movies: Once logged in, explore the featured movies displayed on the main page. Click on any movie card to view its details.

Search for Movies: Use the search bar to search for specific movies by title. Enter the movie title in the search input and press Enter to see the search results.

View Movie Details: Click on any movie card to view detailed information about the selected movie, including its overview, release date, rating, and poster image.

Protected Routes: Test protected routes by attempting to access pages that require authentication, such as movie details. If not already logged in, you'll be redirected to the login page.

Log Out: Finally, test the logout functionality by clicking the logout button. This should clear the current user's session and redirect them to the login page.




#ADD DEPENDENCIES:-
axios: Used for making HTTP requests to fetch movie data from the TMDB API.

react: The core library for building the user interface components of the application.

react-dom: Provides DOM-specific methods that can be used at the top level of a web application to enable React components to be rendered.

react-router-dom: Enables navigation and routing in the application, allowing users to move between different pages and components.

react-toastify: Used for displaying toast notifications to the user, providing feedback for actions such as successful login, registration, or errors.

bootstrap: A front-end framework used for styling the application and creating responsive, mobile-first designs.

dotenv: Allows the application to load environment variables from a .env file, which is useful for storing sensitive information like API keys.

web-vitals: Provides utilities for measuring and reporting web vital metrics like Cumulative Layout Shift (CLS), First Input Delay (FID), First Contentful Paint (FCP), Largest Contentful Paint (LCP), and Time to First Byte (TTFB).

@testing-library/react: A testing utility for React applications that provides a simple and intuitive API for interacting with components in tests.

@testing-library/jest-dom: Extends Jest's built-in assertions with custom matchers for asserting on DOM nodes, enhancing the readability and expressiveness of tests.

jest: A JavaScript testing framework used for writing and running tests to ensure the correctness of the application's behavior.

react-scripts: Provides scripts and configuration used by Create React App for building, testing, and running the application.

sass: A CSS extension language that adds features like variables, mixins, and nested rules, enhancing the organization and maintainability of stylesheets.

node-sass: A Node.js library that provides bindings to LibSass, allowing the application to compile Sass files to CSS.

These dependencies contribute to various aspects of the Movie App project, including data fetching, routing, styling, user feedback, testing, and development workflows.

