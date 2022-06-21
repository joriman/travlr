# CS465-Full-Stack-Dev
## Architecture

For this project, the Travlr Web Application, many types of frontend development were used. 
There are two sides to the application:
 - The main part of this application is the client side, which runs with Express HTML, a framework that runs on the Node.js API. This part of the web application uses Javascript controllers, routes and models (the Model-View-Controller structure). It displays all the different types of informaiton that the client may want to view in order to get information on trips, about pages for contact info, etc.
 - The second part of the application is a Single-Page Application (SPA) that admins can use to fulfill various objectives like adding new trip data, or editing already stored trip data. This side of the application is running Angular, which is a framework that also works on Node.js.

There are a few differences between these two frontends. The two frameworks that are used for these parts allow for differenct use cases and functionality, with the Express framework allowing for the main part of the site to be viewable with HTML pages that can load all the content. It contrasts with how the Angular SPA works. This part of the application is built to support dynamic webpages that allows for a single page that can be viewed on multiple devices and screen sizes. Another difference between Express and Angular is that Angular uses Typescript, which is a superset of Javascript.

The backend used for this application is using MongoDB, a NoSQL dabatabase. This type of database was used as it allows a high level of flexibility and speed. The code written in this course allows us to set up models that we can use as our "schemas", so that the data stored is useable throughout the application. It's also a much better database system when working with cloud based applications, as it's faster when reading and writing, which helps the application to be more user friendly.

## Functionality

JavaScript is a full on programming language used to create the web application, whereas JSON is the JavaScript Object Notation which uses key-value pairs to store data handled by the code written in JavaScript. It's what allows the program to not only store data, but also to do it in a structure. This is the way that we store data when using a NoSQL database aswell, as we now have a structure when storing, querying, and retrieving the data.

The biggest instance of functionality change was the inclusion of security. This was probably the biggest instance in the full stack process where code was refactored to improve functionality and efficiencies. This was very important as it allowed us to not only use more secure protocols like HTTPS, but also helped with security features like logging in and registering.

There were many more smaller instances of refactored code that improved functionality, but this was all made possible (and much more simple) by the reusability of the UI components. This is why Angular is so useful, as it allows us to very quickly and easily add small changes to the UI that make our code and back end functionality easy to use and implement. In this example, a lot of routing and controllers where set up to handle and work with the new models that were put in place. All of the newly added code was used to implement the storing and retrieving of the login and signup data that made security possible. Angular made this easy by allowing for items like buttons that could easily implement these features.

## Testing

From working with web applications, it's possible to understand that endpoints allow us to connect to the URL's and points where our code and application is located, in order to load and use the application. This is where we find our application and render it on the screen in the browser and everything can come together. Securing this process is a multi-step, many aspect approach.

Not only do we have to secure the connections to these endpoints and, usually, the servers that they connect to and retrieve the application and data from, but we also have to secure the interactions that a user would have with not only server, but the data that they would display in the applicaton, as well as data that might get input into the system. It's also very important to lock down a users access to the parts of the application that deal with changing, adding, or removing the data that's displayed and used. That's why using different endpoints for admins is necessary, as it's a great way to lock down the front end functions from unauthorized users.

## Reflection

I think I learned a lot about the processes that go into completing and building a project like this. I also gained some understanding of the scope and things that go into a web application. I think that being able to do this kind of work is very important before getting into the field, so doing this work and course beforehand helps to generate the sense of fimiliarity for future projects. This was a nice starting point and I will hopefully get more understanding and comfort with the material in the future.
