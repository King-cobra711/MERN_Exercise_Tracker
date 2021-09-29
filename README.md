[www.matthew.com.au](https://king-cobra711.github.io/My-Site/)

## Description

This is a simple MERN-stack (Mongodb, Express, Reactjs, Nodejs) application that can perform CRUD actions as follows:
### User
* Get all users (dropdown)
* Create new user

### Exercises
* Get all exercises
* Create exercise
* Update exercise
* Delete exercise

Bootstrap was used for the styling and routes were tested using [Postman](https://www.postman.com/) and data for requests/body info is provided in code comments. 


## Installation

```bash
$ mkdir exerciseTracker
$ cd exerciseTracker
$ git init
$ git pull https://github.com/King-cobra711/MERN_Exercise_Tracker.git
```
Set up your Mongodb collection to be connected to this application. visit [Mongodb](https://www.mongodb.com/) to get started on this. [freeCodeCamp](https://www.youtube.com/watch?v=7CqJlxBYj-M&ab_channel=freeCodeCamp.org) @ 5:00 has a walkthrough on this.

## Running the app

```bash
Install React dependencies:
$ cd to User/Desktop
$ npm i
Install Node dependencies:
$ cd backend
$ npm i
```
Add .env and configure file in the root directory by adding:

SKIP_PREFLIGHT_CHECK=true

Add .env and configure file in the root of the backend directory by adding:

ATLAS_URI= "your-mongodb-connection-string"

```bash
# development
  Start React:
$ In exerciseTracker directory run: npm start
  Start Node:
$ In exerciseTracker/backend directory run: npm start dev

```

## Resources
* [Mongodb](https://www.mongodb.com/).
* [freeCodeCamp](https://www.youtube.com/watch?v=7CqJlxBYj-M&ab_channel=freeCodeCamp.org)



