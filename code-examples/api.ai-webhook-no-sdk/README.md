# API.AI Webhook - No SDK
The purpose of this example is to show you how to do advanced webhook/business
logic without the use of the SDK.

## To run this project:
1. Create a new api.ai project and upload the zip file to the project.
2. `cd actions-on-google-resources/code-examples/api.ai-webhook-no-sdk`
3. `nvm use`
4. `npm i`
6. In a terminal window `npm start`
7. In a second terminal window `../ngrok http 8080`
8. Add your ngrok generated https webhook to your api.ai's project in the fulfillment tab.(Ex: https://006a6cf5.ngrok.io/webhook)

_Note: This project is for demonstration purposes and is not intended for production use._

## APIs used:
- http://thecatapi.com/docs.html
- https://catfacts-api.appspot.com/
