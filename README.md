# MERN-DevConnector
This is a MERN stack application from the "MERN Stack Front To Back" course by Brad Traversy on Udemy.  
It is a small social network app that includes authentication, profiles and forum posts.

## Deployed app
The app has been deployed to https://lee-dev-connector.herokuapp.com
It is deployed on free tier on Heroku and MongoDB so I may need to clear the database once in a while.

## Install on your local machine
Once cloned, add a default.json file in config folder of client
```
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```

## Install server dependencies
```
npm install
```
## Install client dependencies
```
cd client
npm install
```
## From root folder run Express and React
```
npm run dev
```
