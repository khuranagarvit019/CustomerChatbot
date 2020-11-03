# CustomerChatbot

This chatbot can talk to the person calling to a customer care service and ask for important data that will save time at call centres.

Chatbot is hosted at [customerchatbot-v1.web.app](https://customerchatbot-v1.web.app/).

## Setting up your firebase

Installing firebase

`npm install -g firebase-tools`

Logging into firebase

`firebase login`

**Note -** Login with The Semicolons email id.

### Workflow

1. Pull
2. `yarn install` (To install all dependencies)
3. Do your work
4. `yarn build` (To create a production build that will be used to deploy on firebase)
5. `firebase deploy` (To upload the production build on firebase)
6. Commit changes
7. Push to origin
