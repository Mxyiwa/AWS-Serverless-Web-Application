<h1>AWS Serverless Web Application</h1>

<h2>Overview</h2>
<b>We will create a simple serverless web application that enables users to request unicorn rides from the Wild Rydes fleet. The application will present users with an HTML-based user interface for indicating the location where they would like to be picked up and will interact with a RESTful web service on the backend to submit the request and dispatch a nearby unicorn. The application will also provide facilities for users to register with the service and log in before requesting rides.
</b>
<br />
<br />
This project is going to be built by configuring AWS Amplify to host the static resources for the web application with continuous deployment built-in. The Amplify Console is an AWS service that provides a git-based workflow for continuous deployment and hosting of full-stack web apps.
<br />
<br />

<h2>Prerequisites</h2>
<b>To build this project, an AWS account will be required, an ArcGIS (<b>https://www.arcgis.com/index.html#</b>) to add mapping to the app, a text editor, and a web browser.
</b> 

<h2>Application Architecture</h2>
<b>This application architecture is going to comprise of services such as;
</b> 
- <b>AWS Lambda</b>
- <b>Amazon API Gateway</b> 
- <b>Amazon DynamoDB</b> Provides a persistence layer where data can be stored by the API's Lambda function
- <b>Amazon Cognito</b> Provides user management and authentication functions to secure the backend API
- <b>Amazon Amplify Console</b> Provides continuous deployment and hosting of the static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser


<h2>Steps</h2>

- <b>Host a Static Website:</b> 
- <b>Manage Users:</b>
- <b>Build a Serverless Backend:</b>
- <b>Deploy RESTful API:</b>
- <b>Terminate Resources:</b>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
