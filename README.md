# JaxPWA Tracker

## Description

Budget Tracker is a progressive web application that allows users to track their budgets by adding expenses and deposits to their budgets

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Example Usage](#example-usage)
- [License](#license)


## Installation

To install the required dependencies, run `npm install`

This package assumes there is a MongoDB server running on localhost:27017. If your server is running somewhere else, you can edit `server.js` to reflect that.

## Usage

To start the server, run `npm start`. To access the app after starting the server, go to http://localhost:3000 in your browser.



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## User Story

AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 

## Accesptance Criteria

GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
