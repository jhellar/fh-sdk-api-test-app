# Client SDK API test

Tests [Client API](https://access.redhat.com/documentation/en-us/red_hat_mobile_application_platform_hosted/3/html/client_api/) with Client SDK for Cordova.

## How it works
* Prepares environment
  * Creates project in studio
  * Updates connection between client and cloud app
  * Secures endpoints
  * Deploys cloud app
  * Creates policy
  * Clones client app and copies test files in it
* Runs Cordova client app in browser
* Gathers results of testing

## What does it test
* $FH.AUTH
* $FH.CLOUD
* $FH.GETCLOUDURL
* $FH.GETFHPARAMS
* $FH.HASH
* $FH.SEC
* $FH.SYNC

## Prerequisites
* Node.js >= 8
* Cordova

## How to use it
To start the test run:
```
npm install
npm start -- --host=<address> --username=<user> --password=<password> --environment=<env> --prefix=<prefix>
```

## TODO
* $FH.PUSH
* $FH.MBAAS
* $FH.FORMS
