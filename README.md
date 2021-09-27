# MERNG-Moments - Social Media App

A full stack project for a small social media app, using MERNG stack (MongoDB, Express, React JS, Node and GraphQL)

### Note
This repository is still under development and I will continue to add more features to it.

### Project features

- Register user

<img src="./GIFS/register.gif" width=600><br>

- Login user

<img src="./GIFS/login.gif" width=600><br>

- Comment on a post

<img src="./GIFS/comment.gif" width=600><br>

* Delete owned comments

<img src="./GIFS/deleteComment.gif" width=600><br>

* Like and unlike posts

<img src="./GIFS/like.gif" width=600><br>

* View all posts
* View a single post
* Create a post
* Delete owned posts

### Technolgies used

* Node JS
* Express
* Apollo Server
* GraphQL
* Mongoose
* Mongo DB
* React JS
* Apollo Client

### Configuration

In order to test it by yourself you should provide a config.js file with your custom Mongo DB credentials and a secret key to encode your auth token:

```js
module.exports = {
    MONGO_DB: "mongodb+srv...YOUR_MONGODB_CREDENTIALS_AND_DATABASE_HERE",
    SECRET_KEY: "YOUR_AUTH_TOKEN_KEY_GENERATOR_HERE"
}
```
