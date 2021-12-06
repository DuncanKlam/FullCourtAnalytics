
# Deployment

### This application utilises JavaScript, Node.js, and Node Package Manager, as well as several nonstandard packages

#### This application is meant to be connected to a Firestore database for data storage.
### For testing, or to run on a local network, the application can be connected to a JSON server by changing the 'testing' tag in DatabaseAccessor to false

## To Run with firestore:
Put your firestore information in the firebase.cs file
Information is available in SDK Setup and Configuration under Project Settings

## To Run with local DB:
By default, the JSON server runs on port 5000. To change what port it runs on, package.json > scripts > server
Any other information that will need to be changed as a result can be found in LocalDB.js
The local database is stored in the 'fca' folder as db.json

Before beginning the application, open a terminal and run 

> npm run server

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## TO Run Application

To begin application locally, open a terminal in the 'fca' folder and run the command:

> npm install

after that has completed, run:

> npm start

and the application will open in a new window


To stop the application from running, bring focus to the terminal and type:
> 'ctrl+c'
then follow the prompt

Errors will be logged to the browser console
