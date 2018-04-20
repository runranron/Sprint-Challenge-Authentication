<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
In Express, middleware refers to functions that are called between receiving an http request and executing the request. Sessions are stored data that is accessed across requests. bcrypt is an encryption and hashing tool that can be used to secure private data. JWTs are web tokens that are stored in the browser on the client-side.


2.  What does bcrypt do in order to prevent attacks?
Bcrypt hashes the data with user-defined options to determine security-convenience equilibrium. It can also hash and compare a new string with a previously hashed string.

3.  What are the three parts of the JSON Web Token?
Header - type of token and hashing algorithm
payload -  claims about an entity (usually the user)
signature - encoded header, encoded payload, secret, and hashing algorithm, signed to ensure against tampering