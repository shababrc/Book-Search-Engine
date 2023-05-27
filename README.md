# Book-Search-Engine
## Description
We've taken a fully functioning Google Books API search engine built with a RESTful API, and refactored it to be a GraphQL API built with Apollo Server. The app was built using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js server and API.

## User Story
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase

## Acceptance Criteria
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  

## How we did this:
### By:
Set up Apollo Server: We installed the necessary dependencies and configured an Apollo Server to handle GraphQL queries and mutations. This involved defining the GraphQL schema, resolvers, and connecting them to the existing data models.
Replace the existing RESTful API: We refactored the existing codebase to replace the RESTful API endpoints with GraphQL queries and mutations. This allowed us to fetch and modify data using the GraphQL syntax and take advantage of its flexibility and efficiency.
Modify authentication middleware: We made adjustments to the authentication middleware to ensure it functions seamlessly within the context of a GraphQL API. This involved updating the middleware to intercept and process authentication-related requests, such as verifying user tokens or session information.
Create Apollo Provider: We integrated an Apollo Provider into the client-side application. This allowed requests from the client to communicate with the Apollo Server using GraphQL queries and mutations. The Apollo Provider abstracted away the networking and caching logic, simplifying the communication process.
Deployment to Heroku: We utilized Heroku as the hosting platform for our application. We configured the necessary deployment settings and deployed both the client-side and server-side code to Heroku. This made the application accessible and functional in a live production environment.
By completing these steps, we successfully transitioned the application from a RESTful API to a GraphQL API, ensured authentication compatibility, established communication between the client and server using Apollo, and deployed the application to Heroku for public access.

## GitHub Repository
https://github.com/shababrc/Book-Search-Engine 

## Link to Deployed Site
https://gentle-beyond-71300.herokuapp.com/ 

## Credits
Credits to Bryan Swarthout for his amazing teaching and for giving us a great tutorial for this homework. Credits to Shawn Tschoepe as well for his help.

## License
None 