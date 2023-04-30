
# Binance Pay API postman setting

Using this method could test the Binance Pay API on postman.

## How to import and configure

- Download the `BinancePay-api-postman` repository.

- Click the `Import` button. On Postman for Mac, for example, the button is at the top left:

<img src="https://user-images.githubusercontent.com/6247197/235359073-4fe423e3-fd0e-472a-b9f3-8b429c172b74.png" alt="image2" width="75%" height="75%">

- On the `Import` pop-up page, select the `Folder` tab. Click the `Choose folder from your computer` button and choose the root folder of the downloaded repository.

<img width="50%" height="50%" alt="image" src="https://user-images.githubusercontent.com/6247197/235364514-d05007e6-9bd9-4e6e-b77d-de77324f8da1.png">

- Select which collections and environments you would like to import and click the `Import` button.

<img width="50%" height="50%" alt="image" src="https://user-images.githubusercontent.com/6247197/235364587-88f7095c-9e4d-491b-82cf-24a7bee61be3.png">

- Select the `Environments` tab on the left, choose an environment, and set your Api Key and Secret Key by changing the `Current Value` column (see screenshot);
(The `Timestamp`, `nonce`, `Signature`, `Initial Value` fields can be left empty as they’ll be automatically filled by Postman when sending a request.)

<img src="https://user-images.githubusercontent.com/6247197/235367194-b5b634fc-c08f-4464-8b66-f54002d28ef3.png" alt="image3" width="75%" height="75%">

- Select your newly-added environment from the environment dropdown menu. On Mac, this is at top right, to the left of the eye icon.

<img width="60%" height="60%" alt="image" src="https://user-images.githubusercontent.com/6247197/235367369-38120d2d-753c-477f-ac9c-29556c338342.png">


## How to get the api key and secret key of Binance Pay

Binance Pay API key and secret key is different from the Binance Public endpoints api key.

Get the API key and secret key of the Binance Pay account on the Binance Pay merchant dashboard.

<img src="https://user-images.githubusercontent.com/6247197/235358075-948cb4b4-04fd-4532-91a5-cf73b8763199.png" alt="image1" width="75%" height="75%">

## Postman safety practices
The following practices are advised to secure your account's safety:

- Don't use Collections obtained from an unknown source.
- Review the environment JSON file before its usage.
- Don't use any code that you don't understand.
- Make sure that the withdrawal permission **is not enabled** for your API keys.
- When you finish trying out the API, delete your API keys.
