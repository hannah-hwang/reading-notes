# Read: Class 15 Authentication

## OAuth

1. What is OAuth?\
OAuth is adn open-standard authorization protocol or framework that separates authorization and authentication, and allows authentication. They can be based on 3rd party credentials
2. Give an example of what using OAuth would look like.\
An example would be logging into a website using your googlelog-in information.
3. How does OAuth work? What are the steps that it takes to authenticate the user?\
The first wwebsite connects to the second website and requests authorization. Once the request is approved, a unique token is generated and will be asked to authenticate. The user will be given a access token which is given to the first website as proof of authentication of the user.
4. What is OpenID?\
OpenID is is about authorization and doesn't need the website to log in on behalf of the user.

## Authorization and Authentication Flow

1. What is the difference between authorization and authentication?\
Authorization verifies the user's identity, while authentication determines if the user has the rights or permission to proceed.
2. What is Authorization Code Flow?\
The process of exchanging an authorization code for a token.
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?\
Used to add additional security when verifying.
4. What is Implicit Flow with Form Post?\
Implicit flow is intended for public clients and only needs an ID token for user authentication.
5. What is Client Credentials Flow?\
Used when typical login information such as username and password are not necessary. Uses Client ID and Client secret instead.
6. What is Device Authorization Flow?\
Authenticates by asking the user to to go the a link on a device and authorize the device.
7. What is Resource Owner Password Flow?\
Requests that users provide credentials typically using an interactive form.
