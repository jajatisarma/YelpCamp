# Campgrounds-Tour
Welcome to Campgrounds-Tour. A web-based application that allows users to take a virtual tour of different campgrounds. Each campground listing includes photos, descriptions, and additional information about the facilities and nearby attractions.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)

## Project Overview

The Campground Tour project is a web-based application designed to provide users with an immersive virtual tour of various campgrounds. Whether users are avid campers looking for new destinations or curious individuals who want to explore the outdoors from the comfort of their homes, Campground Tour offers an engaging experience that showcases the beauty and amenities of different campsites.

## Features

Campground-Tour provides a user-friendly platform for providing review to campgrounds and explore the campgrounds. Follow these steps to make the most out of the platform:

1. *Sign Up / Log In*: If you're a new user, sign up for an Campgrounds-Tour account. If you're an existing user, simply log in to your account.

2. *Create a Listing*: If you have already explore a campground, you can create a new listing. Provide detailed information about the area, including location, and rental terms. Upload images of the campground.

3. *Browse Listings*: To explore campgrounds, browse the existing listings. 

4. *View Listings on Map*: Utilize the integrated Mapbox map to view the locations of listings ground. This feature helps you to know proper location of the ground.

6. *Provide Reviews*: After you've visited the location, take a moment to provide a review and rating. Your feedback will help other users to make decisions.

7. *Manage Your Listings*: As a user or owner, you can manage your listings by editing or deleting them as needed. Keep your listings up to date to ensure accurate information for others.

8. *Secure and Reliable*: Campgrounds-Tour ensures secure authentication and data protection to provide a safe environment for users to engage in the rental process.

By following these steps, you can navigate Campground Tour and enjoy the benefits of connecting with fellow campers and individuals passionate about outdoor exploration and camping.

## Requirements

To run and understand Campgrounds-Tour, you will need the following:

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

Follow these steps to get Campgrounds-Tour up and running:

1. Clone the repository and navigate to the project directory:
   
   $ git clone https://github.com/SayanAlam/Campgrounds-Tour.git

2. Add the following variables to your .env file, replacing the placeholders with actual values: <br>
CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name> <br>
CLOUDINARY_KEY=<your_cloudinary_key> <br>
CLOUDINARY_SECRET=<your_cloudinary_secret> <br>
MAPBOX_TOKEN=<your_mapbox_token> <br>
DB_URL=<your_database_url> 

3. Install the required dependencies :
   $ npm install
4. Start by running: 
   $ npm start
   
Now your project is up and running at the specified port.
