# Metal Band API

#### A program that allows users to search for a Metal Band on Encyclopedia Metallum as well as generate a random band from that website and see some information thereof. 6/29/17

#### By **Dylan Dills and Andrew Dalton**

## Description



## Planning

1. Configuration/dependencies
  * Install the following packages:

    * Node Packages
      * The following were implemented for use in our Development Environment
        * gulp - allows us to run gulp commands on our project to ease the development process.
        * browser-sync - allows us to see our changes to our project as we save them.
        * browserify - makes our project browser compatible.
        * vinyl-source-stream - puts our browserified source code into a new file.
        * gulp-concat - concatenates our JS files into one.
        * gulp-uglify - consolidates our code into a form that is more easily digestible by the browser.
        * gulp-util - allows us to manage environment variables.
        * del - deletes all the files that are passed as arguments into the command.
        * jshint - analyzes code and warns about parts that don't follow stylistic conventions, or could cause bugs in the future.
        * sass - translates our files into normal CSS .
        * sourcemaps - adds some code which allows us to see which Sass files are responsible for each CSS rule that we see in the browser.
        * bower-files - installs the necessary files on which our front-end package manager depends.

    * Bower Packages
      * The following were implemented in our Production Environment
        * jquery - simplifies HTML document traversing, event handling, animating, and Ajax interactions.
        * bootstrap - provides us with some rudimentary page styling tools.
        * moment.js - allows us to implement time and date related data.

  * It could include a short description of what each does for you

2. Specifications

| Behavior | Input | Output |
| :------- | :---- | :----- |
| User can enter the name of a metal band and receive some info about that band | "Black Sabbath" | "Black Sabbath", "Classic Metal", "United Kingdom" |
| User can get info about a randomly selected metal band | click "Get Random Band" | "Visigoth", "Power Metal", "United States" | 

3. Integration
  * index.html for application entry and navigation and displaying band info.


## Setup/Installation Requirements

* Open your console or powershell command line.
* In your command line, navigate to the desktop or your desired folder destination.
* Copy the project's github address (https://github.com/drewlinn/special-doodle.git)
* Write in your console the command "git clone" and paste the project address afterward and press enter.
* Perform 'npm install' and 'bower install' commands
* Perform the commands 'gulp build' followed by 'gulp-serve' and the application should open in your default web browser.

## Known Bugs
* Country of Origin returns as undefined when a random band is called.

## Technologies Used

  * HTML
  * CSS
  * SASS
  * Bootstrap
  * Javascript
  * jQuery
  * Bower
  * Node
  * Node Package Manager

## Support and contact details

_Email no one with any questions, comments, or concerns._

### License

This software is licensed under the MIT license

Copyright (c) 2017 **Dylan Dills and Andrew Dalton**
