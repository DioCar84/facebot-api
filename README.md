# FaceBot-api - v1
Adaptation of the final project for ZTM web developer course

## Gif Demo
![face bot](Readme/facebot-gif.gif)

## Introduction

This is a facial recognition bot. It will recognize a face in any picture you upload. 
If your picture has more than one face it will only capture one.
This app is connected to a PostgreSQL database.

## What I used

Front-end: HTML, CSS, JavaScript, React
Back-end: Node.js, Express.js
Database: PostgreSQL
Other: Knex, Bcrypt

## What I learned

This project was a big challenge to my Javascript and React knowledge. 
The goal was to create an interactive face recognition, connected to a database which stores user information and credentials.
Through this project I was able to understand how to create a react app and how react components interact with one another.
I learned about state and props and how the parent components pass down information and receive from children components.
I also learned how to integrate the front-end and back-end of an app and how to connect to a database.


## How to use this code
1. Clone this repo
2. In the command line type: 
  ```sh
  npm install
  npm start
  ```
3. You must add your own API key in the `controllers/image.js` file to connect to Clarifai API
4. Add your own database credentials to `server.js` line 12

You can grab Clarifai API key [here](https://www.clarifai.com/)

** Make sure you use postgreSQL instead of mySQL for this code base.
