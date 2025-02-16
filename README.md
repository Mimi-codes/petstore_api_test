## This is an automated API test repository on petstore users endpoint


#### Test site "https://petstore.swagger.io/#/" 

#### The project covers test for the users endpoint
* All values are saved as a variable in the petstore environment

##### The dependencies/libraries used are:
* Newman
* html extra reporter

#### Steps to execute test scripts/Prerequisites
 Below are the steps to set up and execute the test script:
 * Navigate to cmd
 * Run the command: npm i -g newman-reporter-html-extra to install newman and html reporter dependencies
 * Run the command: newman run collection file path -e environment file path -r htmlextra --reporter-htmlextra-export collection file path.html
 * The test report will be generated in the specified directory.


### Notes
The files in this repository are:
* Swagger-Petstore.postman_collection.json: This is the API test collection file that contains the test scripts for the users endpoint
* petstore.postman_environment.json: This is the environment file that contains the values/variables for the API endpoint
* Swagger-Petstore.postman_collection.html: This is the html report of the test