## Installation.
Clone this repository to your local machine.
Navigate to the project directory and run npm install.
Start the server using npm start.


## Dependencies
This application relies on the following dependencies:
React
Axios
jwt-decode
react-router-dom
react-bootstrap


## Usage
After installing and starting the server, navigate to http://localhost:3000 in your web browser to use the 


## application.
The application has two main routes:
Home (/): This is the landing page of the application that displays a welcome message and links to sign up and sign in pages if the user is not authenticated. If the user is authenticated, it displays a navigation bar with links to the market and advisors pages and a logout button.

Sign Up (/signup): This page allows a user to create a new account.

Sign In (/signin): This page allows a user to sign in to an existing account.

Market (/stock): This page displays the stock market.

Advisors (/advisors): This page displays a list of advisors.

## Authentication
This application includes authentication functionality. The useState hook is used to keep track of whether a user is authenticated (isAuth) and the current user (user). If a user logs in successfully, a JSON Web Token (JWT) is generated and stored in local storage. The JWT is used to keep track of whether a user is authenticated across different routes and page refreshes.
## API Communication
This application uses Axios to communicate with an API. The API endpoints are specified in the registerHandler, loginHandler, and logoutHandler functions.
## React Router
This application uses React Router to navigate between different pages. The Routes and Route components are used to define the different routes and their corresponding components. The Link component is used to create links between different pages.


