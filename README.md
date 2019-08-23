# smart-brain

This full stack React Application serves to use the face recognition api. Simply grab a link to any image with a person's face and paste it into the input box. When you submit, it will display the image below as well as have a box surrounding that person's face. Using the technologies listed below, this program is able to handle secured user registration/signin without sending any sensitive information to the client side nor backend. BCrypt allows the app to hash the password to the server side in order to prevent any sensitive information from being retrieved through malicious attacks.

# Technologies Used

- React
- Express
- Knex
- Cors
- BCrypt
- Body Parser
- PostgreSQL

# Steps to reproduce this application to your local machine:
1. Simply clone this repo on your desktop either using SSH or HTTPS
2. Open the cloned folder in your text editor of choice (mine happens to be WebStorm)
3. After it is loaded up onto your editor, please run an ```npm install``` in order to download the required dependencies for this small scale application.
4. When the install is complete, run an ```npm start``` to run the program into your local browser.
     - Please note that if you have a different application running on the same port you will be prompted to either run this on a different port number or to not run the app at all.
