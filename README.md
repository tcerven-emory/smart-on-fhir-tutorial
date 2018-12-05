# emory-patient-data-api-authentication

Code to demonstrate and support authentication using OAuth2 with Smart on FHIR extensions as defined in the [SMART Standalone Launch Sequence](http://www.hl7.org/fhir/smart-app-launch/#standalone-launch-sequence).

## Stable Release

You're reading the documentation for the first and only release.

## Installation

Copy files to web server.

##Usage

- apiDemo_CernerBridge.html
    - Connects to the cerner sandbox.
    - Client ID must be registered and have 'user' scope permissions to resources.
    - User ID and password are 'portal'.
- apiDemo_v2.html
    - Connect to the Emory Patient Data API Gateway.
    - User ID is 'rambo' and password is 'Rambopw.1'
    - Can create your own user ID.
- api_demo_code.html
    - Used as the RedirectUrl of the auth code request by the other pages and also the [mobile app demo](https://serviceforge.atlassian.net/wiki/spaces/PEPDAG/pages/242057284/POC+Sandbox+Explorer+Mobile+App+for+iOS).
    - This is the page to which the  login page will redirect upon succusful authentication.
- vkbeautify.0.99.00.beta.js
    - Dependency in the html files
## Summary

The process of logging in a user into a SoF service is documented with these simple client-side javascript/html pages.

## Examples

- [Cerner Sandbox Authorization Example](https://serviceforge.atlassian.net/wiki/spaces/PEPDAG/pages/230490236/POC+Cerner+Sandbox+Authorization+Example).
- [Cognito Authorization Example](https://serviceforge.atlassian.net/wiki/spaces/PEPDAG/pages/229113857/POC+Cognito+Authorization+Example)
- [Sandbox Explorer Mobile App for iOS](https://serviceforge.atlassian.net/wiki/spaces/PEPDAG/pages/242057284/POC+Sandbox+Explorer+Mobile+App+for+iOS)

