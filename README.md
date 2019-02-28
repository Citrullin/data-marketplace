# Data Marketplace

The Proof of Concept Data Marketplace built using MAM and IOTA Tangle.

## Getting started

Before you can run this application, you will need to install `Node.js` on your machine. Once you've installed `Node.js`, you can use `npm` to run commands listed below.

### Create a Firebase Account

The data-marketplace uses [Firebase](https://firebase.google.com/) as storage solution. 
You need an active Firebase project to use the data-marketplace. Please create one.

### Add config.json in src/

There is an example config.json file in the src directory. Create a config.json file with the same structure.
You can get the information in the Firebase getting started guide for your project.

### To run for Development.

```javascript
npm run install-all

npm run start
```

The application is running on http://localhost:3000


### To run for Production:

#### 1. Install Firebase CLI

Install the Firebase CLI by running the following command:

```javascript
npm install -g firebase-tools
```

#### 2. Log in fo Firebase

Log in to Firebase (for the first time use). Follow instructions on the screen.

```javascript
firebase login
```

#### 3. Install packages

```javascript
npm run install-all
```

#### 4. Build and deploy

```javascript
npm run deploy PROJECT_NAME
```
