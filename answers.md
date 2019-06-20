1. What is the purpose of using _sessions_?
    Sessions allow you to store authentication information in storage for use later.

1. What does bcrypt do to help us store passwords in a secure manner.
    Bcrypt allows a user to use a complex hash algorithm to encrypt a password in one direction.

1. What does bcrypt do to slow down attackers?
    Bcryptjs slows down attackers because the more a user hashes their password the more computing power/time the hacker needs to use to find the password. Bcrypt also allows you to 'salt' a password by adding random values to your original password.

1. What are the three parts of the JSON Web Token?
    The three parts of a JSON web token are the header, payload, and the signature.