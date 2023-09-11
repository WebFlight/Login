# Login
Module with action that lets you log in an anonymous user in a microflow.
This module is commonly (but not exclusively) used in combination with the deeplink module.

The module is created in Mendix version 9.24.2

## How to use

- Always use this action in combination with the "Verify password" java action. This action can be found in the systems module of your app.
- After validating the account information, simply put the java action in the microflow and the user will be logged in. You can now show the desired page from your microflow and the user will be able to continue.

## Dependencies
This module has no dependencies

## Other
Use this module at your own risk. It is your own responsibility to properly mask any passwords that are entered in your Mendix app. Do not forget to tick the "show as password" box when using a regular mendix text box.

## Demo
A demo project can be found at https://login374-sandbox.mxapps.io/index.html?profile=Responsive

## Contribute
If you want to contribute to this module, put in a request or pull request via github (https://github.com/WebFlight/Login).