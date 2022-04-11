# NOSQL-SOCIAL-NETWORK

User Story

AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data

# Acceptance Criteria

GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

## Walkthrough Videos

- [User Routes ](https://watch.screencastify.com/v/MzNH8u7IfxxjiO7uT5QO)
- [Thoughts Routes ](https://watch.screencastify.com/v/qsdPPoOYOEvntN9hiYUw)
- [Friend Routes ](https://watch.screencastify.com/v/xC8Xyj8ziiIi7aBrbkJ2)
- [Reactions Routes ](https://watch.screencastify.com/v/1T9DjhFOwnWT7MsErRzc)

## Table of Contents

- [Installation](#Installation)
- [Contributing](#Contributing)
- [Application](#Starting_Application)
- [Contact](#Contact)

## Installation

Clone the repo files from the link below
You must have mongoDB installed
Run the following at the command line

- npm init -y
- npm install express
- npm install mongoose
- npm install moment

Use Insomnia Core to test API routes

## Starting Application

Start the server
$ npm start

## Contributing

This repository is a demo and is not accepting contributions.

## Contact

Please contact me at ely.cano2033@gmail.com. View more of my work in GitHub at https://github.com/ElyCano.

Created by @ElyCano - feel free to contact me!
