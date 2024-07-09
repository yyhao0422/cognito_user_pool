# Installation guide

To use this template, you must create config.json file in the src/config.json directory.

{
"region": "YOUR_AWS_REGION",
"userPoolId": "COGNITO_USER_POOL_ID",
"clientId": "COGNITO_APP_CLIENT_ID"
}

Create a Cognito user pool to get the value of COGNITO_USER_POOL_ID and COGNITO_APP_CLIENT_ID.

# Command to start the environment

npm install
npm run dev

# Detailed guide and reference

https://docs.aws.amazon.com/cognito/latest/developerguide/getting-started-test-application-react.html
