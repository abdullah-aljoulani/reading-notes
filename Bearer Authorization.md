## Bearer Authorization

### Intro to JWT

**What is a JSON Web Token (JWT)?**

A JSON Web Token (JWT) is a compact, URL-safe means of representing claims between two parties, typically used for authentication and authorization purposes in web applications.

**When should we use JSON Web Tokens?**

JSON Web Tokens (JWTs) are commonly used in various scenarios for authentication and authorization.
EX 1-Stateless Authentication , 2-Single Sign-On (SSO)
3-Cross-Domain Authorization , 4-API Authentication and Authorization

**Claims are expected in which structural component of a JWT?**

Claims are expected to be present in the payload component of a JSON Web Token (JWT). The payload is the second part of the JWT and contains the actual claims or statements about the user or entity being authenticated.

### Are JWTs Secure?

**If I get a JWT and I can decode the payload, how can we call that secure?**

while the payload of a JWT can be decoded, the security of the token relies on the implementation of digital signatures and encryption to ensure the integrity and confidentiality of its contents.

**If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.**

When sending a JSON Web Token (JWT), the sender and receiver must both know a shared secret key. The shared secret key is used for generating and verifying the signature of the JWT.

**Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.**

The content and secret are concatenated or combined together, creating a single string of characters. This combined string represents the confidential information or token in a secure manner.

### JWTs Explained

**Why use JWT?**

1-JWTs allow for stateless authentication, meaning the server doesn't need to store session data for each authenticated user.

2-JWTs facilitate cross-domain communication and can be easily shared between different services or applications

3-JWTs can be used to implement single sign-on (SSO) functionality.

**JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.**

Imagine you have a backpack that you need to carry with you everywhere you go. Now, let's say this backpack is compact and lightweight, making it easy to carry around without feeling burdened. You can take it with you wherever you need to go, whether it's to work, school, or a friend's house.

**What are the three components (the structure) of a JWT signature?**

1- Header:- The header component of a JWT signature contains metadata about the token and the signing algorithm used

2-Payload:- The payload component of a JWT signature contains the actual claims or statements about the user or entity being authenticated.

3-Signature:- The signature component of a JWT is created by combining the encoded header and payload with a secret key  or by using a private key