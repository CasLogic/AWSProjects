This is another simple project where I used five different services—Amplify, Lambda, IAM, API Gateway and DynamoDB.

1. In the initial steps I created a webpage and hosted it using Amplify. The site can be found on the index.html file attached.

2. Then a Lambda function was created to take the values of the base and exponent and return a value to the webpage.

3. An API Gateway to create a POST method to connect Client and Lambda function. After the Gateway was connected the next step was to create a DynamoDB table. The table will capture the value of the Lambda outputs.

4. Because the Lambda function will need access to the the table the IAM Role had to be edited and a DynamoDB table policy needed to be added.

5. After all are connected update the API Gateway endpoint in the script on the index.html page and your Amplify page should now be operational. 
