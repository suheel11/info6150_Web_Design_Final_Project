# TrEx - Your Travel Buddy

New to the city?
Bringing the world together through live experiences
TrEx is a global platform for live experiences that allows anyone to share, find and attend events that fuel their passions and enrich their lives.
From music festivals, marathons, conferences, community rallies, and fundraisers, to gaming competitions and air guitar contests. 
Our mission is to bring the world together through live experiences.
TrEx is a complete web application that allows you to search, view and book ticket for places of recreation and experiences around you .

### Overview of the application
1. This web application allows user to sign up/login. Error handling has been done for the login/register use case.
2. Incorrect username/password won't allow the user to login.
3. On successful registration, email is sent to the registered email address of the user.
4. User can view top places to hang around and experiences, can view all events and search for events and book tickets.
5. User can also download a pdf copy of his/her ticket and can view order history.

### Features/functionalities
1. CRUD Operations performed by user on MyBookings and User Details
2. Authentication/Authorisation using jwt
3. Connect Group Chat to allow access to user to communicate iwth each other
4. Implemented TELEGRAM integration to send queries to Admin User via Channel
5. Implemented NGX Share feature to share the video and other data which is relevant to a entity
6. Performed search, sorting, filtering & pagination on the list of events
7. Detailed view of every event
8. Implemented a circular navigation bar
9. Sent mail upon successful booking using nodemailer
10. Generated a QR Code for attached it with the mail using qrcode API
11. Password encryption
12. Marked event location on Maps using Angular8-google maps
13. Upon successful booking of order, users can download pdf copy of their ticket

### Steps to Setup and Run the Application:
##### Installation and Running:
1. You need to have **angular cli**, **node.js** and **npm** installed on your machine. Once installed, you can check the versions using the below commands

```sh
node -v
npm -v
```
Links for reference:
* [install node.js](https://nodejs.org/en/download/)
* [install angular-cli](https://github.com/angular/angular-cli)

2. Clone the project from GitHub Repository and Install all the necessary packages
```sh
git clone https://github.com/MaheshPrasad44/TrEx-WebProject
cd final-project-cruisers
npm install
```
3. Start node.js server
```sh
node server.js
```

4. Start angular server
```
ng serve
```

5. Start Mongo server
    1. In one shell run
        ```
        mongod.exe
        ```
    2. In another shell run
        ```
        mongo
        ```

6. Open your browser and go to [http://localhost:4200/](http://localhost:4200/)

### Technologies Used:
* Node.js
* Angular 8
* Mongo DB
* Express JS
* REST API
* Nodemailer
* ngx-sharebuttons
* YouTube API
* Reframejs
* pdfjs
* JWT
* Google maps API
* SCSS
* ParticleJS
