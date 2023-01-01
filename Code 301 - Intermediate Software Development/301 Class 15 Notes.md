What is OAuth

1. What is OAuth?

An open-standard authorization protocol or framework.


2. Give an example of what using OAuth would look like.

When someone logs onto a website and it offers more than one opportunity to log on using another website’s/service’s logon.


3. How does OAuth work? What are the steps that it takes to authenticate the user?

1. The first website connects to the second website. 

2. Second website generates a one-time token and a one-time secret unique to the transaction and parties involved.

3. The first site gives this token and secret to the initiating user’s client software.

4. The client’s software presents the request token and secret to their authorization provider.

5. After authentication, the client is asked to approve the authorization transaction to the second website.

6. The user approves a particular transaction type at the first website.

7. The user is given an approved access token.

8. The user gives the approved access token to the first website.

9. The first website gives the access token to the second website as proof of authentication on behalf of the user.

10 . The second website lets the first website access their site on behalf of the user.

11. The user sees a successfully completed transaction occurring.


4. What is OpenID?

OpenID would serve as a single sign-in, vouching for the identities of users.

 

 

(https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html Links to an external site.).

 

 

Authorization and Authentication flows

1. What is the difference between authorization and authentication?

Authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to.


2. What is Authorization Code Flow?

Exchanges an Authorization Code for a token.

 

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

It mitigates single-page apps have special challenges.


4. What is Implicit Flow with Form Post?

Intended for Public Clients, or applications which are unable to securely store Client Secrets.


5. What is Client Credentials Flow?

Authenticates and authorizes the app rather than a user.


6. What is Device Authorization Flow?

Authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device.


7. What is Resource Owner Password Flow?

Requests that users provide credentials (username and password), typically using an interactive form.

 

(https://auth0.com/docs/get-started/authentication-and-authorization-flow