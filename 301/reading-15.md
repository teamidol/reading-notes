# **301 READING CLASS 15**

## **WHAT IS OAUTH**

* OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.

* An example of OAuth is when logging in a website it allows the opportunity to login using another website's login.

* How OAuth works....
1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
3. The first site gives this token and secret to the initiating user’s client software.
4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
6. The user approves (or their software silently approves) a particular transaction type at the first website.
7. The user is given an approved access token (notice it’s no longer a request token).
8. The user gives the approved access token to the first website.
9. The first website gives the access token to the second website as proof of authentication on behalf of the user.
10. The second website lets the first website access their site on behalf of the user.
11. The user sees a successfully completed transaction occurring.

* *OpenID* is a way a user can use a single login for multiple sites.

## **AUTHORIZATION AND AUTHENTICATION FLOWS**

* Authentication is proving you are who you said you are.  Authorization is providing you access to account.

* Authorization Code Flow exchanges an authorization code for a token.

* Authorization Code Flow with Proof Key for Code Exchange (PKCE) require additional security. In addition, single-page apps have special challenges.

* Implicit Flow with Form Post offer a streamlined workflow if the application needs only an ID token to perform user authentication.

* Client Credentials Flow authenticates and authorizes the app rather than a user.

* Device Authorization Flow asks the user to go to a link on their computer or smartphone and authorize the device.

* Resource Owner Password Flow requests that users provide credentials such as username and password.

:thinking: ## Things I want to know more about. 
