## Securing Passwords

**Explain to a non-technical friend how you would safely hash and store a password.**

* Hashing is like a one-way street. It takes your password and converts it into a unique string of characters called a has, The hashed password is stored securely in a database. It's important to ensure that the database is properly protected.

**What is Bcrypt?**

Bcrypt is a widely used hashing algorithm that is specifically designed for securely hashing passwords.

**Why might you use something like Bcrypt?**

1-Protection against brute-force attacks
2-Security against rainbow table attack
3-Adaptive and future-proofing security:

## Basic Auth

**What is Basic Authentication?**

Basic Authentication is a simple and widely supported authentication protocol used in web-based applications and APIs. It is part of the HTTP protocol and provides a straightforward method for authenticating users.

**What properties are necessary in the header of a Basic Auth request?**

The header of a Basic Authentication request must include the following properties:-
1-Authorization :- This is the key property in the header of a Basic Authentication request
2-Credentials :- The credentials are included in the value of the Authorization property

**How are username:password in Basic Auth encoded?**

1-Combine the username and password: Concatenate the username and password together, separated by a colon (":")
2-Encode the combined string in base64: Take the combined string from the previous step and encode it using base64 encoding.

## OWASP auth cheatsheet

**Define the authentication process to a non-technical recruiter.**

Authentication is the process of verifying the identity of someone who wants to access a system, website, or application. It ensures that the person trying to access the system is who they claim to be.

**How should your error messaging respond (both HTTP and HTML)? Why?**

it's important to provide clear and informative messages to users.

*HTTP responses include status codes that indicate the outcome of a request. For error situations, appropriate status codes should be used.

*When an error occurs during the processing of an HTML page, it's essential to display a user-friendly error message that helps users understand what went wrong and how to resolve the issue.