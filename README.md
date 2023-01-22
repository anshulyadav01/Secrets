# Secrets
##### A website that allows you post your deep secrets anonymously. But hey, don't worry, even we cannot access your secrets and passwords as the project has implementation of various levels of **Security** as well as **Authentication**. The project also has the feature of authentication through your Google acount using the Google OAuth20 (secure innit).
- The website uses sessions and cookies implemented on [passport.js](https://www.passportjs.org/) for keeping you logged even when you open the website in another tab.
- Salting and hashing by [bcrypt.js](https://github.com/kelektiv/node.bcrypt.js) is also implemented to secure the passwords (even in the Database itself).
#### Tech Stack Used
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

#### To run this project on your personal machine -
- Open terminal in your corresponding project location, and -


      npm init -y
      npm i express
      npm i mongoose
      npm i ejs
      npm i body-parser
      npm i bcrypt
      npm i dotenv
      npm i express-session
      npm i md5
      npm i mongoose encryption
      npm i passport passport-local passport-local-mongoose
      npm i mongoose-findOrCreate
      npm i passport-google-oauth20

- **Also make sure you have [Studio 3t](https://studio3t.com/download/) installed and connected to your local machine.**
- After all the neccessary node modules are downloaded open your terminal in respective project location and - 
     ```
     mongo
     ```
- Hitting enter will connect the project to Studio 3t.
- Then, to spin-up the server - 
     ```
     nodemon app.js
     ```
- Hitting enter will start a node server on http://localhost:3000.
- To clone this repository -
     ```
     git clone https://github.com/anshulyadav01/Secrets
     ```
