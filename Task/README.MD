# Express API task

## Description

- This project is part of a student project to demonstrate the newly learned Express skills.

## Objective

Using cars in this program, it must be able to execute the following: Access all the cars, Search for a specific car, Delete a car by ID and
Update information of a car by ID.

## Installation and Run

- Download the repository
- Open the folder as a project in your EDI
- Open a new terminal in the folder window
- Type `npm install` in terminal
- To Start - Type `npm start` in terminal

## How To Use

- Open Postman or install it at https://www.postman.com/downloads/
- Type in the below address on Postman to see it first hand

### View All the cars

- Get Request: http://localhost:3000/api

### Search by car Make

- Param = Make
- Get Request: http://localhost:3000/cars/Land_Rover
- Get Request: http://localhost:3000/cars/Hyunday

### Create a New car

- Param = Make, Model, Seats
- Post Request: http://localhost:3000/cars/Toyota&Land Cruiser&8
- Post Request: http://localhost:3000/cars/Toyota&Rav_4&5

### Update car by ID

- Param = ID, Make, Model, Seats
- Put Request: http://localhost:3000/cars/1&Toyota&Carolla_Cross&5

### Delete car by ID

- Param = ID
- Delete Request: http://localhost:3000/cars/3

## Table of content inside the project

- cars.json - Stores all the values in the json array
- index.js - main file with all the operations
- package-lock.json
- package.json
- readme.md
