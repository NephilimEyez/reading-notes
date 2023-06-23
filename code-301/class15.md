# Authentication

## What is OAuth

### What is OAuth?

A word salad. A Framework that describes how you can access secure things after login without having to share the login credential all day?

### Give an example of what using OAuth would look like.

Like when we log in to netlify through our GitHub account

### How does OAuth work? What are the steps that it takes to authenticate the user?

First website connects to the second for the user using OAuth
The second site generates a one use token
The token is passed to the user to then pass to whichever website they were trying to log in to
If they weren't logged it to the second site they may be asked to authenticate
A transaction of some kind is approved on the first site
The user gains access

### What is OpenID?

Authentification rather than Authorization like OAuth. You would log in to a website on their page using this rather than log in to a website by clicking on one of the "Log in with" buttons.

## Authorization and Authentication flows

### What is the difference between authorization and authentication?

Authorization is one site asking another site if you are who you really claim to be.
Authentication is you logging in to your account on that website with a username and password or some kind of key.

### What is Authorization Code Flow?

The steps taken in the code to allow users to log in(Authenticate).

### What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

Something used when you cannot store a client. I think

### What is Implicit Flow with Form Post?

Like the last one, but works well with forms.

### What is Client Credentials Flow?

Authorization?

### What is Device Authorization Flow?

It's when you click a link to authorize a device to log in to that application

### What is Resource Owner Password Flow?

Apparently the least favored way, but it sounds like just normal logging in as far as I can tell


### Further thought

This one is going to be rough for me. There is a lot of terminology and phrases I don't know or recognize and that's my huge weak spot. I am going to have a hard time on this one.