# Ionic PWA Capacitor Data Storage SQLite

The Ionic PWA Capacitor, based on the Ionic PWA Toolkit, is mainly focusing on demonstrating the implementation of the capacitor-data-storage-sqlite plugin.

***Note: This project is a beta and uses early releases of Ionic 4.0.0-beta.16 and Capacitor 1.0.0-beta.11.***


## Getting Started

To start working with this PWA, got to your browser and enter the following address

'''
https://ionicpwacapacitorstorage.firebaseapp.com
'''

## View Me
[ionicpwacapacitor](https://ionicpwacapacitorstorage.firebaseapp.com)

## To run this Project
### Clone the project

clone this repo to a new directory:

```bash
git clone https://github.com/jepiqueau/ionic-capacitor-data-storage-sqlite.git ionic-capacitor-data-storage-sqlite
cd ionic-capacitor-data-storage-sqlite
git remote rm origin
npm install
```

### build the project

```bash
npm run build
npx cap copy web
``` 

### running the PWA apps

```bash
npx cap serve
``` 

### In the App

Click on Test Storage Plugin button

you should see the output of the test:

```
    Storing data successful
    Iskey successful
    Get keys succesful
    Get values successful
    Get keys/values successful
    Remove key successful
    Clear Keys successful
    The test was successful
```
