code .
// opens the code editor of your choice

npm run test
// runs all configured tests in the project

mkdir folderName
// creates a directory with the name folderName

cd folderName
// opens the directory with the name folderName

$ npm i jest@23.6.0 --save-dev
// adds libraries to folder/project and creates dependencies with the version 23.6.0 of JEST

node fileName.js
// opens a file with the name folderName

clear
// clears the screen of previous written code and generated results

rd .git /S/Q
// remove git repository associated with the project

git init
// creates local repository for current project

git add -A
// prepares current files (new and/or moddified) to be commited into local repository

git commit -m "Initial commit"
// adds current files into local repository

git remote add origin https://RemoteName/Proj.git
//Only for initial commit

git push origin master
// adds current files into online repository

git push -f origin master
// forcibly adds current files into online repository, by replacing files that have beed modified
// not recommended for branching and should be used as a last case scenario (e.g.: files have beed modiffied directly in the online repository and you wish not to fetch/pull first before pushing)

git status
//shows which files have been modified and can be commited into local repository

git log
//shows which files have been commited into local repository

npm i express@4.16.3 --save
//install express in order to deploy an API

npm i nodemon@1.18.4 --save-dev
//engine that re-runs an app after updates, without have to manually re-run the entire app after adding new features

npm i body-parser@1.18.3 --save
//allows a request in JSON format

npm run dev
//starts the app in developer mode, as stated in the "start", inside the package.json

npm i redis@2.8.0 --save
//Install redis for this project (redis must 1st be installed on the machine - use Ubuntu bash to install using the commands in the redis documentation)

npm i  cross-env@5.2.0 --save-dev
// Cross set enviroment variable to run server on multiple ports
// Helpfull to start multiple block instances that interact with each other
// Helpfull to run node.js on multiple machines, no mather what the OS
// Helpfull to be able to use dev-peer command

npm i request@2.88.0 --save
//Offers the ability to send a HTTP request

npm run dev-peer
//starts a second instance of the app, in developer mode

npm i elliptic@6.4.1 --save
//creates a public key addresses based on a cryptographic private-public key pair

npm i uuid@3.3.2 --save
//provides a way to generate a truly unique value on the ID field


npm i && npm run dev
//create the necessary dependencies to get the project going

npm i react@16.6.0 react-dom@16.6.0 --save
//install reactJs and react DOM and `save` to create dependencies


npm i parcel-bundler@1.10.3 --save
//bundler module for reactJS, used to serve react components into the browser

npm audit
// check for known vulnerabilities

npm audit fix
// fix knows vulnerabilities but beware that some functionalities might be affected

npm run build-client
//start building the client with parcel bundler, after it was declared in package.json

npm run dev-client
//start building the dev-client with parcel bundler, after it was declared in package.json, in order to not build every time but to open up our project in the browser immediatly to see the changes - we don`t even need to refresh the page

npm i npm-run-all --save-dev
// run-all as a dependency

npm i babel-core@6.26.3 babel-plugin-transform-class-properties@6.24.1 babel-plugin-transform-object-rest-spread@6.26.0 babel-preset-env@1.7.0 babel-preset-react@6.24.1 --save
// additional modules for reactJS that transform certain tags or functions that are deprecated and update them or give an output into the browser console on what the issue could be

npm i react-bootstrap@0.32.4 --save
// boostrap for reactJS

npm i react-router-dom@4.31.1 --save
//split up a single page into various apps thru different endpoints called routes

npm i history@4.7.2 --save
// keep track of various routes where the user has navigated to