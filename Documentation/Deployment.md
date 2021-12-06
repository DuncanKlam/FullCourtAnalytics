
## Deployment

This application utilises JavaScript, Node.js, and Node Package Manager, as well as several nonstandard packages

This application is meant to be connected to a Firestore database for data storage.
For testing, or to run on a local network, the application can be connected to a JSON server by changing the 'testing' tag in DatabaseAccessor to false

TO Run with firestore:
Put your firestore information in the firebase.cs file
Information is available in SDK Setup and Configuration under Project Settings

To begin application locally, open a into the 'fca' folder and run the command:

> npm install

after that has completed, run:

> npm start

and the application will open in a new window


To stop the application from runnin, bring focus to the terminal and type:
> 'ctrl+c'
then follow the prompt

Errors will be logged to the browser console
