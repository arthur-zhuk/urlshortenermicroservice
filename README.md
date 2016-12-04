# URL SHORTENER MICROSERVICE 
## Overview
The URL Shortener allows one to pass a URL as a parameter and receive a shortened URL in a JSON response. If an invalid URL is passed that doesn't follow the valid http://www.website.com format, the JSON response will contain an error instead.

### Using the App

To use the app simply pass in a URL as a parameter as so:
```
https://urlshortenermicroservice.herokuapp.com/new/http://www.github.com
```
### Starting the App

To start the app, make sure you're in the project directory and type `node server.js` into the terminal. This will start the Node server and connect to MongoDB.

You should the following messages within the terminal window:

```
Node.js listening on port 8080...
```

Next, open your browser and enter `http://localhost:8080/`. Congrats, you're up and running!
