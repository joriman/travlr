# CS465-Full-Stack-Dev
## Architecture

For this project, the Travlr Web Application, many types of frontend development were used. 
There are two sides to the application:
 - The main part of this application is the client side, which runs with Express HTML, a framework that runs on the Node.js API. This part of the web application uses Javascript controllers, routes and models (the Model-View-Controller structure). It displays all the different types of informaiton that the client may want to view in order to get information on trips, about pages for contact info, etc.
 - The second part of the application is a Single-Page Application (SPA) that admins can use to fulfill various objectives like adding new trip data, or editing already stored trip data. This side of the application is running Angular, which is a framework that also works on Node.js.

There are a few differences between these two frontends. The two frameworks that are used for these parts allow for differenct use cases and functionality, with the Express framework allowing for the main part of the site to be viewable with HTML pages that can load all the content. It contrasts with how the Angular SPA works. This part of the application is built to support dynamic webpages that allows for a single page that can be viewed on multiple devices and screen sizes. Another difference between Express and Angular is that Angular uses Typescript, which is a superset of Javascript.

The backend used for this application is using MongoDB, a NoSQL dabatabase. This type of database was used as it allows a high level of flexibility and speed. The code written in this course allows us to set up models that we can use as our "schemas", so that the data stored is useable throughout the application. It's also a much better database system when working with cloud based applications, as it's faster when reading and writing, which helps the application to be more user friendly.

## Functionality



## Testing

## Reflection
