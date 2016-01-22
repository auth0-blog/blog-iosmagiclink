# Auth0 Passwordless (Email)

This is the seed project you need to use if you're going to create an app that will use Auth0 Passwordless in Swift and an API that you're going to be developing. That API can be in any language.

## Configuring the example

You must set your Auht0 `ClientId` and `Domain` in this sample so that it works. For that, just open the `Passwordless-Email/Info.plist` file and replace the `{CLIENT_ID}` and `{DOMAIN}` fields with your account information.
> If you downloaded this sample from https://auth0.com/docs while logged in you'll have these values already configured

### Sample API

This sample, after log in, will perfom a request to an API with the user's `id_token`. By default will look for the API in `http://localhost:3001` but you can override it in the entry `Auth0SampleURL` of `Info.plist`. 
To test this sample app quickly we recommend using our [NodeJS API sample](https://github.com/auth0/node-auth0/tree/master/examples/nodejs-api)

## Running the example

In order to run the project, you need to have **Xcode 7** installed.
Once you have that, just clone the project and open the file `Passwordless-Email.xcworkspace`

Enjoy your iOS app now :).

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
