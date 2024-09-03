Employee Management System
Contents

    Brief Summary
    Aims and Motivation
    Technologies, Requirements, and Software Tools
    Design

<a name="summary"></a>
Brief Summary

This project is a full-stack Employee Management System designed using Spring Boot and MySQL for the back-end, and React for the front-end. It provides a RESTful API that supports CRUD (Create, Read, Update, Delete) operations for managing employee data. The application is tested using Postman and is fully integrated with a React-based user interface using Axios for HTTP requests. It is actively used by a community sports club to manage their employee records.

<a name="aims"></a>
🎯 Aims and Motivation

The primary goal of this project is to develop a robust full-stack application that utilizes Spring Boot and MySQL for back-end development, and React for front-end development. The project is driven by a passion for learning and self-improvement, aiming to gain hands-on experience in building a comprehensive application from the ground up.

<a name="tech"></a>
⚙️ Technologies, Requirements, and Software Tools
Programming and Scripting Languages

    Java
    JavaScript
    HTML
    CSS
    JSON

Frameworks & Libraries

    Spring Boot (Back-end)
    React (Front-end)
    Bootstrap (Front-end & Back-end)

npm Requirements (React)

    npm axios
    npm react-router-dom

Other Software Tools

    MySQL Workbench: Used to store employee information in the back-end.
    DataGrip: Assisted in managing the database and supporting back-end development.
    Postman: Used to test API endpoints for PUT, GET, POST, and DELETE requests.

<a name="design"></a>
✏️ Design
Front-end Technology Stack
React & npm Packages

    React is used for building the user interface and managing user interactions. It retrieves data from the back-end and presents it on the front-end for user visibility.
    Axios is used to make HTTP requests to the back-end, supporting CRUD operations and real-time updates.
    React Router DOM is employed to manage client-side routing, rendering different components based on URL paths, and creating navigation links within the application.

Bootstrap

    Bootstrap is utilized to create a responsive navigation bar and layout for displaying employee information in a user-friendly table format.

Back-end Technology Stack

    Java, along with the Spring Boot framework, is used to handle the business logic and operations of the web application.
    Spring Boot facilitates the creation of user models, handles database connections, and supports custom exception handling.
    MySQL Workbench and DataGrip are used for storing and managing employee data.

RESTful API

    The application uses a RESTful API designed in Spring Boot, with endpoints to handle various HTTP requests for managing employee data.