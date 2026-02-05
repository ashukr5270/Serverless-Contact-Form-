Serverless-Contact-Form (API -> Function -> DB):-

https://8cgr9b5o0l.execute-api.ap-south-1.amazonaws.com/ashishkr


![Image](https://github.com/ashukr5270/Serverless-Contact-Form-/blob/main/Image.jpeg?raw=true)


AWS:

Create a DynamoDB Table: Set up a simple NoSQL table to store form entries.

Create a Lambda Function: Write code (e.g., in Python/Node.js) to process the incoming data and save it to 
DynamoDB.

Create an API Gateway Endpoint: Configure an HTTP endpoint that triggers your Lambda function on a POST 
request.

Update Frontend: Point your HTML form's action to the API Gateway URL.
