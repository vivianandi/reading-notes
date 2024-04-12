# Authentication

## What is OAuth
What is OAuth?
- Protocol for authorization, allowing secure access to resources without sharing credentials
- Used by applications to access user data from other applications without revealing passwords


Give an example of what using OAuth would look like.
- Logging into a website using your Google or Facebook account without sharing your username and password with that website

How does OAuth work? What are the steps that it takes to authenticate the user?
- User Authorization: User grants permissions to a third-party application to access their resources
- Authorization Grant: The application receives an authorization grant, usually in the form of a token, from the authorization server
- Token Exchange: The application exchanges the authorization grant for an access token
- Access Resources: The application uses the access token to access the user's resources on the resource server

What is OpenID?
- An authentication protocol that allows users to be authenticated by co-operating sites (known as relying parties), using a third-party service
- It allows users to log in to multiple unrelated websites without having to create a separate identity for each

## Authorization and Authentication flows
What is the difference between authorization and authentication?
- Authentication: Process of verifying the identity of a user, ensuring they are who they claim to be
- Authorization: Process of determining what permissions an authenticated user has, and what actions they are allowed to perform

What is Authorization Code Flow?
- Involves exchanging an authorization code for an access token after the user authenticates

What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
- Enhanced security version of the Authorization Code Flow, used by public clients (e.g., native apps) to protect against authorization code interception attacks

What is Implicit Flow with Form Post?
- OAuth 2.0 flow primarily used by browser-based applications (JavaScript) where tokens are returned directly in the URL fragment
- Enhanced version of the Implicit Flow, with the tokens returned in the body of a form post

What is Client Credentials Flow?
- OAuth 2.0 flow used by confidential clients to obtain an access token on behalf of themselves, rather than a user
- Typically used for machine-to-machine communication

What is Device Authorization Flow?
- OAuth 2.0 flow used in devices with limited input capabilities (e.g., smart TVs, game consoles)
- Involves displaying a code to the user on a secondary device, which they enter on the primary device to authenticate

What is Resource Owner Password Flow?
- OAuth 2.0 flow where the user's username and password are exchanged directly for an access token
- Considered less secure and discouraged in favor of other flows whenever possible
