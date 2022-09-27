## Online Learning Application

Have you ever registered or joined an online course where every material about the topic is explained in videos? This project is a mini app that is similar to that. 

This Project is written with two server-side programming languages PHP and Javascript (Node JS), uses MySQL as Database, and implements microservices architecture in which each service is separated.

## Services

 - **User Service**
https://github.com/hakimfauzi23/learnApp__backend_service_users
 Features: CRUD Users, Authentication 

 - **Media Service**
https://github.com/hakimfauzi23/learnApp__backend_service_media
Features: Manage Media (Upload, Delete, Get) with Base64 encryption.

 - **Course Service**
https://github.com/hakimfauzi23/learnApp__backend_service_course
Features: Manage Courses such as Mentors, Courses, Chapters, Lessons (Video), and others. (core of the projects)

 - **Order Payment Services**
https://github.com/hakimfauzi23/learnApp__backend_service_order_payment
Features: Manage Orders and payments , handle webhooks from Midtrans.

## API Gateway
This API gateway have function for handling traffic between client and server, so  everytime clients need to communicate with servers must be through the API Gateway, provided with JSON web token so the API Request is more secure.
https://github.com/hakimfauzi23/learnApp_backend_api_gateway
