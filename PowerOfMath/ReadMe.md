This is another simple project where I used five different services—Amplify, Lambda, IAM, API Gateway and DynamoDB.

In the initial steps I created a webpage and hosted it using Amplify. Then a Lambda function was created to take the values of the base and 
exponent and return a value to the webpage.

Use API Gateway to create a POST method to connect Client and Lambda function. After the Gateway was connected the next step was to create a Dynamo
DB table. The table will capture the value of the Lambda outputs. Because the Lambda function will need access to the the table the IAM Role had 
to be edited and a DynamoDB table policy needed to be added.
