<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
    Middleware is separate software that serves as the glue between two applications.
    A session is a place to store data that you want access to across requests. Every user that visits a website has a unique session.
    bcrypt is a password hashing function.
    JSON Web Token (JWT) is a way of securely transmitting information between two parties.


2.  What does bcrypt do in order to prevent attacks?
    bcrypt allows us to increase the cost which allows us to limit the total number of hashes possible within a certain amount of time. This prevents an attacker from simply attempting to use a large library of potential passwords and hashing them all.

3.  What are the three parts of the JSON Web Token?
    Header
    Payload
    Signature
