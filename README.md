## Project Overview

This is a matched-betting-tracker application for tracking user's matched betting activities, has support for Oauth 2.0 authentication.

# Server setup

```
cd server
npm install
```

# Client setup

```
cd client
npm install
```

### Run server

```
cd server
npm run dev
```

### Run client

```
cd client
npm run serve
```

API level tests are done using Mocha and Chai. 

### Run tests

```
npm test
```


# Required environment variables

Recommended you have a .env file inside the server folder with the following variables:
```
GOOGLE_CLIENT_ID= 
GOOGLE_CLIENT_SECRET=
GOOGLE_REDIRECT_URL=

DATABASE=           //name of the database
CLIENT_URL=
```


### TODO:

1. Setup previlage based access to APIS
2. Setup Oauth2.0 in the frontend
3. Apply a front end library