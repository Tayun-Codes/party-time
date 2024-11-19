# Party Time! Full-Stack App
This is a full-stack application that allows users to make events and (not yet developed) invite people to rsvp.
Create an account or login and see a list of events you are hosting! If you want to host an event, hit the "Make Event" button and fill out the form. 

## How It's Made:
Party Time is built using the following technologies:

- **Node.js**: Utilized for server-side development.
- **JavaScript (JS)**: Employed for both client and server-side functionality.
- **MongoDB**: Used as the database to store unique user and event data.
The core functionality is implemented on the server side using CRUD (Create, Read, Update, Delete) operations, enabling the handling of user RSVPs and event specific data. On the client side, event listeners are employed. Users initiate CRUD functions by filling out forms and clicking buttons on the interface.

**Key Packages Used:**

- **mongoose**: Facilitates interaction with MongoDB.
- **passport**: Handles user authentication.
- **express**: Provides a framework for building the web application.

## What I Learned
- **Dynamically create unique documents** to store user and event specific data
- **Code Organization** to clearly route client and server side data, navigating 

## Upcoming Features
Soon you will be able to invite your friends to RSVP and leave a comment for the host, you, and prepare your party~

## Have fun!
Interact and host your own parties with this full-stack app [here](https://party-time-qts2.onrender.com/)!

If you would like to download my code and connect your own MongoDB database to it make a database.js document in the root folder with this format:
```
module.exports = {

    'url': 'mongodb cluster Url',
    'dbName': 'dbName'
};
```
Make sure that in the url you include the dbName between "mongodb.net/" and "?retryWrites" should look like this: 'url': '...mongodb.net/dbName?retryWrites...'

