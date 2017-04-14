# confusionRistorante2
confusionRistorante is a project builded during 'Front-End JavaScript Frameworks: AngularJS' course by The Hong Kong University of Science and Technology. 
This project is a simple web site integrated with angular and client-server communication.

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