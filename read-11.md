# Authentication

### What is OAuth?

OAuth is an authentication protocol that allows you to approve one application interacting with another on your behalf without giving away your password.

### Give an example of what using OAuth would look like.
The simplest example of OAuth in action is one website saying “hey, do you want to log into our website with other website's login?” In this scenario, the only thing the first website – let's refer to that website as the consumer – wants to know is that the user is the same user on both websites and has logged in 

### How does OAuth work? What are the steps that it takes to authenticate the user?
1. Step 1 – The User Shows Intent.
1. Step 2 – The Consumer Gets Permission.
1. Step 3 – The User Is Redirected to the Service Provider.
`<Bitly directs Joe to Twitter for authorization>`
1. Step 4 – The User Gives Permission.
1. Step 5 – The Consumer Obtains an Access Token.

### What is OpenID?

OpenID Connect is an interoperable authentication protocol based on the OAuth 2.0 family of specifications. ... OpenID Connect allows for clients of all types, including browser-based JavaScript and native mobile apps, to launch sign-in flows and receive verifiable assertions about the identity of signed-in users.

----------------------------------------------------

### What is the difference between authorization and authentication?
![](https://lh3.googleusercontent.com/proxy/njF7fbis9pIAFyMtLWbXGI5rm2WBiUYaxIWrReyJ4ECm24GBPlEw9ESF5hnc_b6S-5zFoaPDvOThi_uh5SOjKYPBnDf6J4l9SlbLyj2R175dfOFvmKgB20KTZj8ScmBdUqNpdA_o7lS6fLIQFU6h3H0w0cDK5r6i5rVJslzIABBUiKTHoB6XFVTA8A)


### What is Authorization Code Flow?

Authorization code flow is used to obtain an access token to authorize API requests. ... Access tokens while having a limited lifetime, can be renewed with a refresh token. A refresh token is valid indefinitely and provides ability for your application to schedule tasks on behalf of a user without their interaction.

### What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users. This flow is considered best practice when using Single Page Apps (SPA) or Mobile Apps. PKCE, pronounced “pixy” is an acronym for Proof Key for Code Exchange.

### What is Implicit Flow with Form Post?
Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.

### What is Client Credentials Flow?
The Client Credentials flow is a server to server flow. There is no user authentication involved in the process. ... This flow is useful for systems that need to perform API operations when no user is present. It can be nightly operations, or other that involve contacting OAuth protected APIs.

### What is Device Authorization Flow?
The OAuth 2.0 Device Authorization Grant (formerly known as the Device Flow) is an OAuth 2.0 extension that enables devices with no browser or limited input capability to obtain an access token. This is commonly seen on Apple TV apps, or devices like hardware encoders that can stream video to a YouTube channel.

### What is Resource Owner Password Flow?
The Resource Owner Password Credentials flow allows exchanging the username and password of a user for an access token and, optionally, a refresh token. The primary difference is that the user's password is accessible to the application
