# NodeJS APIs with Redis

## Introduction
This is the basic project to give an example of use of Redis with NodeJS. In this project we expose an API in which Github username is passed as parameter and as the result we get the total stars combined on the repositories by the user.

## Installation
1. Clone the repository
2. Install npm modules: `npm install`
4. Start up the app: `node app`
5. Visit our `API` endpoint and provides a **username** as a URL parameter
```
	http://localhost:5000/api/facebook
```

## We Use
1. The GitHub API to get information about all the user's repositories
2. NodeJs to handle the HTTP requests and compute the total stars
3. redis as a caching layer to speed things up!