it is the project which is based on like netflix where user can watch movies and give it their reviews

Backend: Java with Spring Boot

Java: The backend of your application is built using the Java programming language.
Spring Boot: Spring Boot is used as the framework for building the backend. It simplifies the development of Java-based applications by providing conventions and defaults for common tasks.
MongoDB: MongoDB is used as the database to store your application's data. MongoDB is a NoSQL database that stores data in flexible, JSON-like documents.
Frontend: React.js

React.js: The frontend of your application is built using React.js, which is a popular JavaScript library for building user interfaces. React.js allows for the creation of reusable UI components and provides a declarative approach to building interactive user interfaces.
API Calls: The React.js frontend interacts with the backend through API calls. This means that the frontend sends HTTP requests to the backend to fetch data (e.g., using the Fetch API or Axios).
Communication between Frontend and Backend:

The React.js frontend communicates with the Java Spring Boot backend by making HTTP requests (e.g., GET requests) to specific API endpoints.
The backend processes these requests, interacts with the MongoDB database, and returns the requested data to the frontend in a structured format, typically in JSON.
Project Flow:

Users interact with the React.js frontend by interacting with the UI components.
When data is needed, the React.js frontend sends requests to the Spring Boot backend through defined API endpoints.
The Spring Boot backend handles these requests, interacts with the MongoDB database to retrieve or manipulate data, and sends the data back to the React.js frontend.
The React.js frontend then updates its UI to display the received data.
