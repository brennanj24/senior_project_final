Welcome to my senior project!

This project is a web-based application that calls a c++ backend functionality. This 
backend is called, 'SCA', and it provides feeback to syudents on their code.

My part of this project was to create a GUI to allow the user to interact with this 
backend, allowing the user to upload their own file and see the feeback our backend
can provide.

Included in my repository are the three main files that run my GUI.

#index.html - file to contain the actual HTML of my webpage, providing titles, instructions,
buttons, and the forms they need to use the application properly. 

#app.js - I used Node.js to create an endpoint for my server to send/receive requests at. 
This file also contains functionality for the HTML file to call and invoke in the background.  

#webpageStyle.css - A prettu standard css file, just to decorate and style my webpage to make
it look aesthetically pleasing. 

This applications runs on a Google Cloud VM instance, and therefore does not have any pre-requisites 
for the user to be able to use our app. Everything the app needs is downloaded directly onto the server
itself. 

To access the webpage, navigate to 'http://34.162.169.186:3000' to access the application.

Users can upload 1 file at a time, and this application only works with c++ (.cpp) files.
