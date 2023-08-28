# Yelp Camp
Welcome to Yelp Camp. A web-based application that allows users to take a virtual tour of different campgrounds. Each campground listing includes photos, descriptions, and additional information about the facilities and nearby attractions.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)

## Project Overview

The Yelp Camp project is a web-based application designed to provide users with an immersive virtual tour of various campgrounds. Whether users are avid campers looking for new destinations or curious individuals who want to explore the outdoors from the comfort of their homes, Yelp Camp offers an engaging experience that showcases the beauty and amenities of different campsites.

## Features

Yelp Camp provides a user-friendly platform for providing review to campgrounds and explore the campgrounds. Follow these steps to make the most out of the platform:

1. *Sign Up / Log In*: If you're a new user, sign up for an Yelp Camp account. If you're an existing user, simply log in to your account.

2. *Create a Listing*: If you have already explore a campground, you can create a new listing. Provide detailed information about the area, including location, and rental terms. Upload images of the campground.

3. *Browse Listings*: To explore campgrounds, browse the existing listings. 

4. *View Listings on Map*: Utilize the integrated Mapbox map to view the locations of listings ground. This feature helps you to know proper location of the ground.

6. *Provide Reviews*: After you've visited the location, take a moment to provide a review and rating. Your feedback will help other users to make decisions.

7. *Manage Your Listings*: As a user or owner, you can manage your listings by editing or deleting them as needed. Keep your listings up to date to ensure accurate information for others.

8. *Secure and Reliable*: Yelp Camp ensures secure authentication and data protection to provide a safe environment for users to engage in the rental process.

By following these steps, you can navigate Yelp Camp and enjoy the benefits of connecting with fellow campers and individuals passionate about outdoor exploration and camping.

## Requirements

To run and understand Yelp Camp, you will need the following:

- Node.js
- Express
- MongoDB
- Mapbox API keys
- Cloudinary account (for image hosting)
- EJS (Embedded JavaScript) templating engine
- HTML/CSS
- Bootstrap
- JavaScript

## Installation
### To run this project on your system:
Clone the repository and navigate to the project directory:
```
   $ git clone https://github.com/jajatisarma/YelpCamp.git
```
Create an .env file and add values to the following variables:
```
CLOUDINARY_CLOUD_NAME=<Your Cloudinary cloud name>
CLOUDINARY_KEY=<Your Cloudinary key>
CLOUDINARY_SECRET=<Your Cloudinary secret>
MAPBOX_TOKEN=<Your Mapbox token>
DB_URL=<Your MongoDB atlas URL or local MongoDB URL>
```
Make sure you have [MongoDB](https://docs.mongodb.com/manual/installation/) installed on your system


Install dependencies using npm:

```
$ npm install
```
And then run the application with
```
$ npm start
```
   
Now your project is up and running at the specified port.
