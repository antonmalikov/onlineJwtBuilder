Online JSON Web Token Builder
=============================

Quick Start
---------------
1. docker build . -t localjwtgen
1. docker run -d -p 3080:3000 --name jwt --rm localjwtgen

NodeJS-based web application used to generate signed valid JSON Web Tokens to be used for testing. You can include both standard and custom claims, as well as specify your own symmetric signing key.

Future plans for:
- Saving form data to browser local storage
- "Import Token" button, to populate the claims from an existing token

The live site for this application is here: http://jwtbuilder.jamiekurtz.com


Developer Guide
---------------

1. Ensure [NodeJS](http://nodejs.org/download/) is installed
1. Run `npm install` from this project folder to install/configure all modules
1. Run `npm start` to start the server
1. Browse to http://localhost:3000 to view the site


