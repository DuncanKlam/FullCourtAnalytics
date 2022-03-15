
## Development

All that is needed to replicate our systems are Node.js and Javascript, and a backend of some sort, be it a fake JSON server or a real one, like firebase

# DEPENDENCIES:
Firebase
React
Node.js
Javascript
Json-server (optional fake back-end, and included in package.json)

React Dependencies:
Available in package.json


# FOLDER STRUCTURE:

FCA > main source folder, contains all high level information (package manager information, docker container information/build file, local database)

src > contains source code

public > contains production build of site

components > inner props of the pages

contexts > files for the storage of data in accordance with the react hook UseContext

css > style sheets, broken into individual component and general page styles

data > static unchanging data, currently a spot for coach contact csv's

firestore > objects to get specific data from the firestore

pages > all the outer containers for any page on the site

# CONFIG:
Put your personal firebase information in the firebase.cs file
The addition of any Routes should be done in App.js


# DEVELOPMENT: 
To start the app, make sure your terminal is within the fca folder, and run  > npm start

To start the fake back end, open a second terminal within the fca folder and run > npm run server
 - to utilize the fake server and not try to get information from the Firebase database (or whichever you want to connect to), you must navigate to the DatabaseAccessor.jsx file (located in /src folder) and change the variable getDataSource from Accounts to LocalDB


# ERRORS AND OTHER THINGS
A main reason for errors in the current application is becuase the information does not persist through page reloads, so check to see if this is still an error

Else, should you encounter an error, find the closest line above where the error happens and type 'debugger' into the source code and save it. Then, rerun the app and open the console in the webpage to walk through the code steps in the debugger. If you don't have the console open, the debugging won't register and the page will run like normal.