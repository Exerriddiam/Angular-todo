# Angular todo App

## Overview

### What is this app for?

This is a todo app. it helps users to keep track of anythings that they have todo.

### What deos it do?

This app will allow users to register and login. Once the users have done that, they'll be able to create items to add to thier todo list. Once they've created to
they'll be bale to update the status of each item and even delete items!.

### How deos it work?

This app uses JSON web tokens to authenticate users and keep them logged in. All the data is consumed from an API hosted on Heroku using AngularJS. this site is styled with
Bootstrap.

## Features

### Existing Features
- None yet!

### Features Left to Implement
- User Based Features
	- Registration
	- Login
	- Logout
- Todo Based Features
	- Creating Todo Items
	- Retrieving Items
	- Updating Todo Items
	- Deleting Todo Items

## Tech Used

### Some of the tech used includes:
- [AngularJS](HTTPS:angularjs.org/)
	- we use **AngularJS** to Handle page routing, we also use it to make calls to the REST API and build custom directives.
- [Bootstrap](http://getstrap.com/)
	- we use **Bootstrap** to give our project a simple, responsive layout.
- [npm](https://www.npmjs.com/)
	- we use **npm** to help manage some of the dependencies in our application
- [Bower](https://bower.io/)
	- **Bower** is used to manage the installation of our libraries and frameworks.


## Contributing

### Getting the code up and running
1.Firstly you will need to clone this repository by running the *'''git clone <project's Github URL>'''* command
2.After you've done that you'll need to make sure that you have npm and bower installed
	 - you can get npm by installing Node from -[here](https://www.npmjs.com/)
	 - Once you have done this you'll need to run the following command: *npm install -g bower # this may requre sudo on Mac /Linux* 
3.Onc **npm** and **bower** are installed, you'll need to install all of the dependencies in *package.json and bower.json*

	npm install

	bower install

4.After those dependencies have been installed you'll need to make sure that you have **http-server** installed. you can
install this by running the following: *npm install - g http-server # this also may require sudo on Mac/Linux*
5.Once **http-server** is installed run *http-server
6.The project will now run on -[localhost](localhost:8080)
7.Make changes to the code and if you think it belongs in here then submit a pull request

