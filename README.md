
# Student test and result management MICROSERVICE

- It is a **node.js**, **express.js** based microservice which includes all the functions required for student management system.
- It uses node.js and express for creating and managing backend server.
- It uses **MongoDB atlas** for database i.e mongoose package.
- It has functions to create **Admin** and **Student** user.
- It has other important admin functions like **creating papers, setting paper date, entering data into papers, viewing result of students**.
- Students can fill their **details, view the test paper assigned to them, give the test, view their result**.
 


## Run Locally

Clone the project

```bash
  git clone https://github.com/deepakjyadav01/Student_Test_and_Result-Microservice.git
```

Go to the project directory

```bash
  cd server
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start || node app.js || nodemon app.js
```

- You can install postman or ARC to test API.
- check the routes in router.js and fill the body within POST section i.e the fields required.
- for eg. for student admin registration the required details within body are username, email, password and cnfpass.
- the URL for admin registration is http://localhost:4500/admin/adminregister. similarly, you can use various URL's for various API.

   
## Tech Stack


**Server:** Node, Express

**Database:** MongoDB Atlas
