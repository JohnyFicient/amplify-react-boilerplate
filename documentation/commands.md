# Create project
npx create-react-app amplify-react-boilerplate
cd amplify-react-boilerplate

# Start amplify
npm install --save aws-amplify
npm install --save aws-amplify-react
amplify init
```
? Choose your default editor: Vim (via Terminal, Mac OS only)
? Choose the type of app that you're building javascript
Please tell us about your project
? What javascript framework are you using react
? Source Directory Path:  src
? Distribution Directory Path: build
? Build Command:  npm run build
? Start Command: npm start
? Do you want to use an AWS profile? Yes
? Please choose the profile you want to use default
```

# Start adding stuff
amplify add hosting
amplify add auth
```
... use default ...
```
amplify add api
```
? Please select from one of the below mentioned services GraphQL
? Provide API name: awsreactbootstrap
? Choose an authorization type for the API Amazon Cognito User Pool
Use a Cognito user pool configured as a part of this project
? Do you have an annotated GraphQL schema? No
? Do you want a guided schema creation? true
? What best describes your project:
? What best describes your project: Single object with fields (e.g., “Todo” with ID, name, description)
? Do you want to edit the schema now? (Y/n) n
```
amplify push
amplify publish
