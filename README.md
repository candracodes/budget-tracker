# Budget Tracker
![badge](https://img.shields.io/badge/license-MIT-brightgreen)

## Description
This application adds functionality to an existing Budget Tracker application to allow for offline access and functionality.

## TODO:
1. Resolve heroku issue (does it need a key + value like MongoAtlas) ✅
2. Resolve offline error: "service-worker.js:55  Uncaught (in promise) TypeError: Failed to fetch at service-worker.js:55" ✅
3. Resolve offline error: "index.js:116 POST http://localhost:3000/api/transaction net::ERR_FAILED" ✅
4. Resolve manifest error: Actual height (169px) of Icon http://localhost:3000/icons/icon-192x192.png does not match specified height (192px) ❌
5. Resolve manifest error: Actual height (452px) of Icon http://localhost:3000/icons/icon-512x512.png does not match specified height (512px) ❌

## Table of Contents
- [Important URLs](#urls)
- [Foreword](#foreword)
- [Usage](#usage)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Mockup](#mockup)
- [Packages](#packages)
- [Contributors](#contributors)
- [License](#Licensing)

## URLs
- [Github Repo](https://github.com/candracodes/budget-tracker)
- [Deployed Heroku Application](https://candra-budget-tracker.herokuapp.com/)
- [Full Acceptance Criteria](./assets/README.md)

## Usage
- To run this application locally:
```
npm start
```

## User-Story

```md
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
```

## Acceptance-Criteria
```md
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.
```
## Mockup
![screenshot1](/assets/screenshot1.png)

## Packages

This project is created using the following packages
- [Node.JS](https://nodejs.org/en/)
- [Express.JS](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://www.npmjs.com/package//mongoose)
- [Morgan](https://www.npmjs.com/package/morgan)

## Contributors
* David Johnson, my BCS tutor

## Licensing
The project is made possible with the following Licensing:
- [MIT](LICENSE)



