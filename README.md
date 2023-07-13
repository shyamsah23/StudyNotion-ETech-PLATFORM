
# StudyNotion

StudyNotion is a fully functional Ed-tech platform that enables users to create, consume, and rate educational content. The platform is built using the MERN stack, which includes ReactJS, NodeJS, MongoDB, and ExpressJS.

StudyNotion aims to provide:-

A seamless and interactive learning experience for students, making education more accessible and engaging.

A platform for instructors to showcase their expertise and connect with learners across the globe.


## Roadmap

- System architecture: The high-level overview of the platform's components and diagrams of the architecture.

- Front-end: The description of the front-end architecture, user interface design, features, and functionalities of the front-end, and frameworks, libraries, and tools used.

- Back-end: The description of the back-end architecture, features and functionalities of the back-end, frameworks, libraries, tools used, and data models and database schema.


- API Design: The description of the API design, list of API endpoints, their functionalities, and sample API requests and responses.

- Payment Integration: Students will purchase and enrol on courses by completing the checkout flow that is followed by Razorpay integration for payment handling.


- Cloud-based media management: StudyNotion uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.



## Documentation

[React](https://react.dev/learn)
[ExpressJS](https://devdocs.io/express/)
[MongoDB](https://www.mongodb.com/docs/)
[TailWind](https://tailwindcss.com/docs/installation)
[RazoPay](https://razorpay.com/docs/#home-payments)
[Cloudinary](https://cloudinary.com/documentation)

## Installation

Install Project with npm ( Clinet )

```bash
  npm creat-rect-app my-app
  cd my-project
```

Install Project with npm ( Server )

```bash
  npm init -y
  npm install
  npm i express
  npm i nodemon
  npm i concurrently
```
## Packages Used



To run this project, you will need to add the following packages

`@reduxjs/toolkit`
`charts.js`
`react-toast`
`react-icons`
`react-hot-toast`
`react-rating-star-component`
`react-type-animation`
`bcrypt`
`cloudinary`
`cookie-parser`
`dotenv`
`razorpay`
`nodemailer`
`express`
`jsonwebtoken`
`mongoose`
`react-otp-input`
## Running Tests

To run tests, run the following command

```bash
  npm run dev

```


## Technology Used
 - React JS
 - Tailwind Css
 - Express JS
 - MongoDB
 - Razopay
 - Cloudinary
 - PostMan
## Features

**FRONT_END:**

To build the front end, I use frameworks and libraries such as ReactJS, which is a popular JavaScript library for building user interfaces. I also use CSS and Tailwind, which are styling frameworks that help make the user interface look good and responsive. Additionally, I use some npm packages to add extra functionality to the front end. To manage the state of the application, we use Redux, which is a popular state management library for React. 

- For Students 
  * HomePage
  * Course List
  * Course content
  * User Detail
  * Edit User information

- For Admin 
    * HomePage
   * Instructor DashBoard ( Pie Chart )
   * Course management Pages
   * View And edit profile Detail



**BACK_END:**

The back end of StudyNotion provides a range of features and functionalities, including:

- User authentication and authorization: Students and instructors can sign up and log in to the platform using their email addresses and password. The platform also supports OTP (One-Time Password) verification and forgot password functionality for added security.

- Course management: Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.

- Payment Integration: Students will purchase and enrol on courses by completing the checkout flow that is followed by Razorpay integration for payment handling.

- Cloud-based media management: StudyNotion uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.

- Markdown formatting: Course content in document format is stored in Markdown format, which allows for easier display and rendering on the front end.





## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

` REACT_APP_BASE_URL`

` MAIL_HOST`
` MAIL_USER`
` MAIL PASS`

` JWT SECREAT`

` FOLDER NAME`
` CLOUD_NAME`
` API_KEY`
` API_SECREAT`

` RAZOPAY_KEY`
` RAZOPAY_SECREAT`

` MONGO_DB_URL`
` PORT`



## Tech Stack

**Client:** React, Redux, TailwindCSS

**Server:** Node, Express , PostMan

**DataBase:** MongoDB

**PayMent Integration:** RazoPay

**Cloud_Based_Media_Management:** Cloudinary


## Lessons Learned

- Desgin of Schemas / Models ( Student , Instructor and Course)

- MongoDB connection with backend Using Mongoose.

- Cloudinary And razoPay connection with backend.

-  API Calls from Client To Server.

- React Redux For Efficent State Mnagement ( Avoid Props Drilling ).

- Use of React charts for Better Data Visulaization.

- Importance of Local Stoarege.

- JWT Token for Authentication and Authorization.

- Use of Nodemailer to send the mails.

- Use of React- Router .

- Middlewares for Authentication.

- PostMan For API Testing


