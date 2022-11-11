## United Tutoring

- [Introduction](#introduction)
- [Features](#features)
- [Authors](#authors)
- [Built With](#built-with)
- [AWS Services](#aws-cloud-services-used)
- [Other API](#other-api)
- [Getting Started](#getting-started)
- [Acknowledgments](#acknowledgments)

## Introduction 

* One to One Tutor and student session management
United Tutoring is an online platform for one-to-one tutoring. This online platform caters to two
types of users: tutors who impart knowledge and students who seek knowledge. Students can use
this platform to interact with registered tutors and get all their questions answered when they are
having difficulty understanding a concept or want to learn something new. Besides improving their
overall understanding of a subject or topic, this also assists them in trying out and learning
something new. A user can be both a tutor as well as a student.

* Tutors must create an account and list their skills and experience in their expertise. Registered
students can search by skill and obtain a list of tutors who specialize in that subject. Students can
then go to each tutor's profile and arrange an appointment with whichever tutor appears to be
pertinent to their question. Moreover, tutors will be able to enter their available dates and time
range, which will subsequently be transformed into one-hour slots. A real-time schedule of tutors'
slots will be available for students, and they will be able to schedule accordingly. When a student
requests a booking, it appears on the tutor's my booking requests page. A link to a Zoom meeting
will be sent to both participants if the tutor approves the booking request. If the tutor rejects the
request, the student will receive an email notifying them of the rejection. Every hour, a Cronjob
runs to update the status of sessions that have expired. In addition, tutors can view their entered
availabilities and all requests, including accepted, rejected, and pending requests.

* *Date Created*: 01 MAY 2022
* *Last Modification Date*: 26 JULY 2022
* *Demo URL*: <https://www.youtube.com/watch?v=lJaXV4cw8fo/>
* *Git URL*: <https://git.cs.dal.ca/courses/2022-summer/csci4145-5409/group-23/-/tree/main/> 

## Features
* User Profile Management
* Tutor's Availability Management
* Booking Sessions
* Accepting or Rejecting Requests
* Email Notification
* Real Time Status Management
* Searching based on S`kills


## Authors

* [Vivekkumar Patel]  - *(Developer)*
* [Keyur Vaghani](https://github.com/KeyurVaghani) - *(Developer)*
* [Manali Shah](https://github.com/Manalishah1) - *(Developer)*

## Built With

United Tutoring has been build with following technology stack.

* [![HTML][HTML.com]][HTML-url]
* [![CSS][CSS.com]][CSS-url]
* [![Java script][javascript.com]][javascript-url]
* [![Node][Node.com]][Node-url]
* [![React][React.js]][React-url]
* [![Express][Express.com]][Express-url]
* [![Jwt][Jwt.com]][Jwt-url]
* [![AWS][AWS.com]][AWS-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]

##  AWS Cloud Services Used

1. [AWS Cognito](https://aws.amazon.com/cognito/)
2. [AWS Lambda](https://aws.amazon.com/lambda/)
3. [AWS S3](https://aws.amazon.com/s3/)
4. [AWS DynamoDB](https://aws.amazon.com/dynamodb/)
5. [AWS EventBridge](https://aws.amazon.com/eventbridge/)
6. [AWS API Gateway](https://aws.amazon.com/api-gateway/)
7. [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)
8. [AWS Simple Notification Service](https://docs.aws.amazon.com/elastic-beanstalk/)
9. [AWS Cloud Formation](https://aws.amazon.com/cloudformation/)

##  Other API Used

1. [Zoom API](https://devforum.zoom.us/t/help-understanding-how-to-create-meeting-using-backend/8496)
2. [Moment js](https://momentjs.com/)

## Getting Started

To have a local copy of this project up and running on your local machine, refer the sections below.
### Prerequisites

First you need to install the following software / libraries / plug-ins

* Node.js
* npm

See the following section for detailed step-by-step instructions on how to install this software / libraries / plug-ins

### Installing

Installation of Node.js and npm can be found at https://nodejs.org/en/

Run the following commands to check successful installation:

* node -v
* npm -v

To run this project on local follow the below steps:

* Run 'git clone https://git.cs.dal.ca/aabhaas/group_14_backend_csci5709' for cloning files of this repository to local machine.
* Run 'npm install' for installing dependencies.
* Run 'npm run build' to build the app.
* Run the app using 'npm start'.
* Open browser and run http://localhost:8080/ to run the app in the browser.

## Acknowledgments

* [Node.js](https://nodejs.org/en/docs/)
* [Amazon Cognito Identity SDK](https://www.npmjs.com/package/amazon-cognito-identity-js-node)
* [AWS SDK for Javascript](https://www.npmjs.com/package/aws-sdk)
* [AWS Cloud Formation](https://docs.aws.amazon.com/cloudformation/index.html)
* [React Formik](https://formik.org/)

<!-- LINKS & IMAGES -->
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Node.com]: https://badges.aleen42.com/src/node.svg
[Node-url]: https://nodejs.org/en/
[CSS.com]:  https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white
[CSS-url]:  https://www.w3schools.com/css/
[HTML.com]: https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white
[HTML-url]: https://www.w3schools.com/html/
[javascript.com]:https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColo=%23F7DF1E
[javascript-url]:https://www.javascript.com/
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[AWS.com]: https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white
[AWS-url]: https://aws.amazon.com/
[Express.com]:https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB
[Express-url]: https://expressjs.com/
[Jwt.com]:https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens
[Jwt-url]: https://jwt.io/


<!-- LINKS & IMAGES For services used -->
