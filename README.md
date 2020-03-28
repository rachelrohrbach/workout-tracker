# NoSQL Workout Tracker

## Table of Contents
* [General Info](#general-info)
* [User Story](user-story)
* [Technologies](#technologies)
* [Screenshot](#screenshot)
* [Credits](#credits)
* [License](#license)

## General Info
The Workout Tracker applications allows the user to view and track daily workouts. Workout Tracker uses a Mongo database with a Mongoose schema and the routes are handled with Express. When the user loads the page, they are given the option to create a new workout, or continue with their last workout. The user can also view a 10-day range of the duration of exercises as well as average weight per day for the exercises on the stats page.
First the user must use the following command to install dependencies required:
```sh
npm install
```
Next the user can run 
```sh
npm run seed
```
which will load some starter data for the application. The application is then invoked with the following command:
```sh
node server.js
```

## User Story

As a user, I want to be able to view create and track daily workouts. I want to be able to log multiple exercises in a workout on a given day. I should also be able to track the name, type, weight, sets, reps, and duration of exercise. If the exercise is a cardio exercise, I should be able to track my distance traveled.

## Technologies
This project is created with: 
* Express.js
* Node.js 
* HTML
* CSS
* Chart.js
* JavaScript
* MongoDB
* Mongoose

## Screenshot 
![app home screenshot](public/assets/img/workout-screenshot.png)
![stats screenshot](public/assets/img/stats-screenshot.png)
Link to deployed heroku app: 


# Credits
The front-end code was provided as starter code by my course. I consulted my course GitLab repository, Mongoose (https://mongoosejs.com/docs/guide.html), and Stack Overflow (www.stackoverflow.com) in creating my project. 

## License
MIT License

Copyright (c) [2020] [Rachel Rohrbach]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.