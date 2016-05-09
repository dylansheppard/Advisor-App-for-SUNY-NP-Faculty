# Advisor-App-for-SUNY-NP-Faculty
Web Application to be used by SUNY New Paltz Computer Science department!



BACKEND (MODEL):
Tech Stack: The backend is written entirely in Javascript using NodeJS and Express. I've been dabbling with serving page views with Handlebars, but I'm probably going to drop that in the official version.

All node modules will be included. However, you will probably need to install Node on the server itself. 

You can download the latest verson here: (this app uses version 4.3.0): https://nodejs.org/en/download/

There is one node file that must be running for the applciation to work: "users.js"
This file keeps track of users and listens for logins. 

Once a valid login is reached, then the node file that controls student information will be available.

Right now, the users.js can only be ran with "node users.js" command. The upside of this is that the server is only active when it needs to be. This is more secure, but won't be a valid option if you want students to be able to access this information.

If that's the case, contact me, and I can modify it to support constant login. There's an npm library called "forever" that will run node servers indefinitely. 

FRONTEND (VIEW/CONTROLLER):
Tech Stack: AngularJS, Bootstrap, a bit of JQuery 
All included via CDN, no need to configure anything unless you want to update version.
NOTE: I using Angular 1 because Angular 2 is way to obstrusive (and I don't like change :< )

I plan on including a config.js file that includes global variables that faculty may want to change.

