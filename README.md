# confusionRistorante2
confusionRistorante is a project builded during 'Front-End JavaScript Frameworks: AngularJS' course by The Hong Kong University of Science and Technology. 
This project is a simple web site integrated with angularm client-server communication and tests.

# Installation
1. Make sure you already have NodeJS intalled in version v7.4.0
2. Intall bower globaly `npm install -g bower`(if in Mac or Linux maybe sudo is required)
2. Install gulp globaly `npm install -g gulp` (if in Mac or Linux maybe sudo is required)
3. Install json server globaly`npm install json-server -g` (if in Mac or Linux maybe sudo is required)
4. Into project folder install all dependencies:
    1. `bower install`
    2. `npm install`
5. Into /json-server folder run `json-server --watch db.json` to start the server
6. Into root folder run `gulp watch` to start the project

Obs.: If when running `gulp watch` results in a error page, reload the browser.

# Tests
This project also have unit tests with karma and jasmine
1. Make sure you have karma installed, if not: `npm install karma-cli` (if in Mac or Linux maybe sudo is required)
2. Make sure you have protactor intalled, if not: `npm install protractor -g` (if in Mac or Linux maybe sudo is required)
3. Run the tests, in test folder:
    1. To run unit tests in prompt run `karma start karma.conf.js`
    2. To run the end to end test in prompt run `protractor protractor.conf.js`