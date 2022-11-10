# Google OAuth2 - Web Server Example

> _This project was modified from the Node.js example here:_\
> _https://developers.google.com/identity/protocols/oauth2/web-server#example_

This project has been modified to console log the URL that initiates the OAuth
process; To start a server that redirects you to the OAuth url _(the intended_
_example code)_, set the ENV `START_SERVER=true`.

_(The purpose of console logging the URL is to see how the `scopes` of_
_space-delimited URL values are supposed to be encoded, for use in Postman_
_testing)._

[Google's OAuth docs](https://developers.google.com/identity/protocols/oauth2/web-server).

## Project setup

1. Clone and install dependencies:

   ```sh
   npm i
   ```

2. Copy `.env-sample` to `.env` and update the ENV values

3. Start the project:

   Set `START_SERVER=false` to console log the OAuth Step 1 url;\
   Set `START_SERVER=true` to start a server that redirects to the OAuth url.

   ```sh
   node ./index.js
   ```
