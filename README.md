# Restaurant Info

A Web application of sharing restaurant information using Node.JS.

The application allows user to add/edit/delete restaurant informations for other users to view. User can leave/delete  reviews on each restaurant.

## Demo

[https://web-restaurantinfo-nodejs.onrender.com](https://web-restaurantinfo-nodejs.onrender.com)

Visitor authority: Can only View restaurant info and user reviews 

User(need login) authority: Can add new restaurant info, edit and delete the info. Can leave/delete reviews.

### Demo User Account

User 1
 - Username: ```user1```
 - Password: ```user1```
 
 User 2
 - Username: ```user2```
 - Password: ```user2```

## Technology Stack

The application uses following technologies:

- Node.js : JavaScript runtime environment
- Express.js : Web Framework for Node.js
- MongoDB Atlas : Cloud-based NoSQL Database
- Mongoose: Object Data Modeling (ODM) library for MongoDB and Node.js
- Cloudinary: Cloud-based media management platform for image and storage and delivery
- Mapbox: Open-source mapping platform for custom maps and location-based applications

## Features

- User authentication: Register/Login/Logout
- Create/Update/Delete restaurant information
- Create/Delete review of each restaurant
- Visualize address of restaurant on a custom map

## Start the Application

### 1. Clone the repository
```
git clone https://github.com/Raphaelhhc/RestaurantInfo-NodeJS
```

### 2. Change into the project directory
```
cd RestaurantInfo-NodeJS
```

### 3. Install the project dependencies
```
npm install
```

### 4. Set environmental variables
```
CLOUDINARY_CLOUD_NAME= <Enter your Cloudinary name>
CLOUDINARY_KEY= <Enter your Cloudinary key>
CLOUDINARY_SECRET= <Enter your Cloudinary secret key>
MAPBOX_TOKEN= <Enter your MAPBOX Token>
MONGODB_URI= <Enter your MongoDB Atlas URI>
CONFIG_SECRET= <Enter password encoding key>
```
* If no MongoDB Atlas account: refer to [https://www.mongodb.com/docs/atlas/](https://www.mongodb.com/docs/atlas/) to create one.
* If no Cloudinary account: refer to [https://cloudinary.com/documentation](https://cloudinary.com/documentation) to create one.
* If no MAPBOX account: refer to [https://docs.mapbox.com/](https://docs.mapbox.com/) to create one.

### 5. Run the application server
```
node app.js
```

### 6. Open your web browser and visit [http://localhost:3000](http://localhost:3000)

## Screenshots

 - Cover Page
 ![App Screenshot](https://res.cloudinary.com/doe9mfetd/image/upload/v1686478837/Restaurant-Info_GITHUB/Cover_u2rrez.png)
 - Restaurant List Page
![App Screenshot](https://res.cloudinary.com/doe9mfetd/image/upload/v1686478837/Restaurant-Info_GITHUB/Restaurant_List_ifvgsu.png)
 - Login Page
![App Screenshot](https://res.cloudinary.com/doe9mfetd/image/upload/v1686478837/Restaurant-Info_GITHUB/Login_vxcswt.png)
 - Create New Restaurant Page
![App Screenshot](https://res.cloudinary.com/doe9mfetd/image/upload/v1686478836/Restaurant-Info_GITHUB/New_Restaurant_odaplc.png)
 - Restaurant Detail Page (As Visitor)
![App Screenshot](https://res.cloudinary.com/doe9mfetd/image/upload/v1686478837/Restaurant-Info_GITHUB/Reataurant_Detail_Visitor_rwscik.png)
 - Restaurant Detail Page (As User)
![App Screenshot](https://res.cloudinary.com/doe9mfetd/image/upload/v1686478837/Restaurant-Info_GITHUB/Restaurant_Detail_User_vl0sgi.png)