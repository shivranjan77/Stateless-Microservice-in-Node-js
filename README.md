# Stateless-Microservice-in-Node-js
Stateless Microservice In Node js
 A simple stateless microservice in Nodejs, with two major functionalities -
 
 Authentication 
 Image Thumbnail Generation
 
 Public Endpoints
 The Login Request body should contain an arbitrary username/password pair. 
 Treat it as a mock authentication service and accept any username/password. 
 Return a signed Json Web Token(JWT,https://jwt.io/) which can be used to validate future requests.
 Protected Endpoint 
 The following endpoint should be protected. 
 The JWT obtained in the “Login” endpoint must be attachedto each request.
 If the JWT is missing or invalid, these endpoints should reject the request.
 Create Thumbnail Request should contain a public image URL. Download the image, resize to50x50 pixels, and return the resulting thumbnail.
 
 
 Steps To Run:--
 1- install node js
 2. install express by opening cmd then type npm install express
 3. open the package.json file and install all the dependencies individually by opening cmd then type:-
    npm install body-parser
    npm install ejs
    npm install image-downloader
    npm install jsonwebtoken
    and all the other dependencies if prompt any on your pc in same way.
 
 4.Then go to the root directory of project in cmd and type npm start or node app.js to start server you will get this output "app running on port 3000"
 5. Then goto web Browser and type "http://localhost:3000" which will show you output as per question like web-page not found thumbnail
 6. In same way type "http://localhost:3000/login" it will show jwttoken
 7. In same way type "http://localhost:3000/image" it will give output as thumbnail according to question.
 
 
     THank YOu.
