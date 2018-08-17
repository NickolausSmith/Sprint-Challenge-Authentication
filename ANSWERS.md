<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
        Middleware works with our routes to check authorized users on our routes. Sessions send cookies to a user and then use that to authenticate. Bcrypt is used to hash/encrypt passwords. JWT is a token that holds a user's encrypted data. 
2.  What does bcrypt do in order to prevent attacks?
        Hashes the password to make it harder to decrypt.
3.  What are the three parts of the JSON Web Token?
        Payload contains the data of the token/the user. Header contains the more specific data only relating to the token. And signature holds the secret to encrypt the key. 