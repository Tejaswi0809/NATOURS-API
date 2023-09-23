<h1 align="center">
  <br>
  <a href="https://natours-api-z82r.onrender.com/"><img src="https://github.com/lgope/Natours/blob/master/public/img/logo-green-round.png" alt="Natours" width="200"></a>
  <br>
  Natours
  <br>
</h1>

<h4 align="center"> Natours is an awesome tour booking site built on top of <a href="https://nodejs.org/en/" target="_blank">NodeJS</a>. The site offers a variety of features that allow users to search and book tours, manage their bookings, and update their profile. Authentication and authorization features are also included, allowing users to log in and log out. The tour page allows users to check out tours on a map and see user reviews and ratings. Users can pay for tours using a credit card.</h4>

 <p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#demonstration">Demonstration</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#api-usage">API Usage</a>
  <a href="#build-with">Build With</a>•
  
</p>



## Key Features

* Authentication and Authorization
  - Login, Signup and logout
* Tour
  - Manage booking, check tours map, check users' reviews and rating
* User profile
  - Update username, photo, email, and password
* Credit card Payment


## Demonstration
#### Home Page :
![natoursHomePageonline-video-cutt](https://user-images.githubusercontent.com/58518192/72606801-7ebe0680-3949-11ea-8e88-613f022a64e5.gif)

#### Tour Details :
![tourOverviewonline-video-cutterc](https://user-images.githubusercontent.com/58518192/72606859-a0b78900-3949-11ea-8f0d-ef44c789957b.gif)

#### Payment Process :
![paymentprocess-1-ycnhrceamp4-7fW](https://user-images.githubusercontent.com/58518192/72606973-d9eff900-3949-11ea-9a2e-f84a6581bef3.gif)

#### Booked Tours :
![rsz_bookedtours](https://user-images.githubusercontent.com/58518192/72607747-6a7b0900-394b-11ea-8b9f-5330531ca2eb.png)




## How To Use

### Book a tour
* Login to the site
* Search for tours that you want to book
* Book a tour
* Proceed to the payment checkout page
* Enter the card details (Test Mood):
  ```
  - Card No. : 1346 5678 1234
  - Expiry date: 05 / 28
  - CVV: 198``
* Finished!



### Manage your booking

* Check the tour you have booked in "Manage Booking" page in your user settings. You'll be automatically redirected to this
  page after you have completed the booking.

### Update your profile

* You can update your own username, profile photo, email and password.



## API Usage
Before using the API, you need to set the variables in Postman depending on your environment (development or production). Simply add: 
  ```
  - {{URL}} with your hostname as value (Eg. http://localhost:8080 or http://www.example.com)
  - {{password}} with your user password as value.
  ```



<b> API Features: </b>

Tours List 👉 https://lgope-natours.onrender.com/api/v1/tours

Tours State 👉 https://lgope-natours.onrender.com/api/v1/tours/tour-stats

Get Top 5 Cheap Tours 👉 https://lgope-natours.onrender.com/api/v1/tours/top-5-cheap



## Build With

* [NodeJS](https://nodejs.org/en/) - JS runtime environment
* [Express](http://expressjs.com/) - The web framework used
* [Mongoose](https://mongoosejs.com/) - Object Data Modelling (ODM) library
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - Cloud database service
* [Pug](https://pugjs.org/api/getting-started.html) - High performance template engine
* [JSON Web Token](https://jwt.io/) - Security token
  

* [Postman](https://www.getpostman.com/) - API testing
  
  

