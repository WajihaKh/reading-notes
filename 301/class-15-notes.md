# Authentication

## What is OAuth?

OAuth is a way for you to use your credentials from one website to securely access another website or service without sharing your username and password directly.

## Example of OAuth

Imagine you want to sign in to a new website using your Google account. Instead of creating a new account, you click on "Sign in with Google." The website then redirects you to Google's login page. After you enter your Google credentials, Google sends back a special token to the website, allowing it to access your account information without seeing your password.

## How OAuth Works

1. You visit a website that needs access to another service.
2. The website sends you to the service (like Google) to log in.
3. After you log in, you're asked to approve the website's request to access certain information.
4. The service gives the website a token.
5. The website uses this token to access the information it needs on your behalf.

## What is OpenID?

OpenID is a way to use one set of login credentials (like your Google account) to sign in to multiple websites without creating separate accounts. It's about securely logging in from one place to another online.

## Authorization vs Authentication

- Authentication confirms a user's identity.
- Authorization decides what actions or resources a user can access based on their identity and permissions.

## Authorization Code Flow

Used by regular web apps to securely exchange an authorization code for tokens with the authorization server.

## Authorization Code Flow with PKCE (Proof Key for Code Exchange)

Enhanced version used by mobile and native apps for added security, using a Proof Key for Code Exchange (PKCE) during authentication.

## Implicit Flow with Form Post

Simplified flow for public clients to obtain ID tokens for user authentication, suitable for applications unable to securely store client secrets.

## Client Credentials Flow

Used by machine-to-machine (M2M) applications where the application itself is authenticated and authorized.

## Device Authorization Flow

Used by input-constrained devices that ask users to authorize via another device (computer or smartphone) instead of directly authenticating on the device.

## Resource Owner Password Flow

Not recommended but used by trusted applications to directly request user credentials for authentication when other flows are not feasible.
