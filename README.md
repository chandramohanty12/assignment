# restapi-app
NodeJS / React sample rest app for AWS CI/CD pipeline

A REST to do list Musicians API created with Node and a React frontend. Deployed and ran on Elastic Beanstalk environment of AWS cloud 
deployed through AWS Developers Tool codepipeline

######################################################################

Development environment: Amazon Linux AMI 2018.03.0 (HVM) / AWS t2.micro

Hosted at: http://restapiapp-env.7bwrkm8qwm.us-west-2.elasticbeanstalk.com/
Fully functional version of the app hosted at this url

Node version: v13.1.0  
NPM Version: v6.12.1
React version 16.9.0  
 

######################################################################
Make sure npm and node are installed in AWS EC2 instance

## Available Scripts

In the project directory, we can run:

### `npm start`

Runs the app in the development mode.
Open http://localhost:3000to view it in the browser.

The page will reload if you make edits to code.

### `npm test`

Launches the test runner in the interactive watch mode.


### `npm run build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
The app is ready to be deployed!

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

### Application Deployment

TO DEPLOY TO AWS Beanstalk

This app is hosted on a AWS Beanstalk

##################################################################

TO DEPLOY THROUGH JENKINS

Untested

Change environment variables according to your environment and run the pipeline through Jenkinsfile in this directory



