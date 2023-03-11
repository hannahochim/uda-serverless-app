# Serverless To-Do App

This is the final project in the Udacity Cloud Developer Course.


## Deploy Backend
- cd backend
- npm install
- npm install --save-dev serverless-iam-roles-per-function@next 
- serverless
- serverless deploy --verbose

## Deploy Frontend
- cd client
- npm install
- npm run start


## plugins
- npm install serverless-aws-documentation --save-dev
- npm install --save-dev serverless-iam-roles-per-function@next
- npm install serverless-webpack --save-dev
- npm install serverless-reqvalidator-plugin

## Additional
I encountered some error with */node-modules/express-serve-static* . The commands below resolved this:
- npm install typescript@4.1.6
- npm install -D @types/express-serve-static-core@4.17.30

apiEndpoint = `https://g24rp1t797.execute-api.us-east-2.amazonaws.com/dev`
