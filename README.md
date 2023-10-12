# Yelp-Camp
I worked on this project as a part of my course on Udemy, namely The Web Developer Bootcamp 2023. Finding information regarding camping locations may be challenging, and the information 
that is accessible may be dispersed across several websites, making it challenging to obtain all you want. This project is my first time using NodeJS to create a website. Therefore, I did a lot of 
research related to NodeJS such as reading documentation and researching related frameworks. 

Then, I started developing the website by listing the features that would be applied. For the User 
Interface, I use HTML, CSS, JavaScript, EJS (Embedded JavaScript), and Bootstrap. For server-side, I use Express.js. Then, I modeled the database using MongoDB and integrated it with 
Express.js using Mongoose. I also implement basic security such as sanitizing by using Mongo Sanitize to prevent injection of database syntax. As an architectural style, I use REST. 

In making this 
project I also use NPM packages and utilizing various dependencies such as Passport for user authentication and authorization, Mapbox for maps and geocoding, Cloudinary for images storage, 
etc. I applied a strict verification system, which consists of client-side verification and server-side verification using JOI to avoid accessing certain pages using platforms such as Postman (without 
going through the User Interface). From this project, I learned to understand the big picture of the stages in real application development.


## How to Install

1. Install [NodeJS](https://nodejs.org/en/download).
2. Install [mongodb](https://www.mongodb.com/docs/manual/administration/install-community/) and for Windows users install [mongosh](https://www.mongodb.com/docs/mongodb-shell/install/) too.
4. Clone this repository.
5. Open command prompt in the cloned directory (where **package.json** is located) and run `npm install`.
6. Create a [Cloudinary](https://cloudinary.com/) account and create a new environment in clodinary. Then look for Cloud Name, API Key, and API Secret.
7. Make a .env file, then set these values: <br>
CLOUDINARY_CLOUD_NAME=your_cloud_name <br>
CLOUDINARY_KEY=your_API_key <br>
CLOUDINARY_SECRET=your_API_Secret <br>
8. Before running, make sure to run **mongod** from start menu or applications.
9. Once everything is done, run `node app` to start the application.
10. `localhost:3000` should be link to the website.
