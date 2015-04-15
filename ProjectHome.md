# Google+ JavaScript API Starter Project  #

This starter project demonstrates use of the Google+ APIs and development best practices. You can use it as a starting point for building your own Google+ applications.

## Getting Started ##
Once you're ready to dive in to the code simply download the [zip archive](http://code.google.com/p/google-plus-javascript-starter/downloads/detail?name=google-plus-javascript-starter.zip) and follow the instructions below.

  1. Visit the [Google API Console](https://code.google.com/apis/console/?api=plus) to generate your developer key, OAuth2 client id, and register the location of your application.
    * From the "Services" screen, activate access to "Google+ API".
    * Click on "API Access" in the left column
    * Click the button labeled "Create an OAuth2 client ID"
    * Give your application a name and click "Next"
    * Select "Web Application" as the "Application type"
    * Under "Your site or hostname" enter the  domain where you will be hosting your application.
    * Click "Create client ID"
  1. Edit `index.html` with the consumer key and developer key you obtained in step 1.
    * Update 'insert\_your\_oauth2\_client\_id' with your oauth2 client id.
    * Update 'insert\_your\_developer\_key' with your developer key. This is listed under "Simple API Access" at the very bottom in the [Google API Console](https://code.google.com/apis/console/#:access)
  1. Visit http://localhost/googleplus/index.html

# Related Resources #
  * [google-api-javascript-client](http://code.google.com/p/google-api-javascript-client/) - The library this starter project is based on.
  * [Google+ API reference docs](http://developers.google.com/+/)