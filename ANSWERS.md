<!-- Answers to the Short Answer Essay Questions go here -->

1. What is the purpose of using _sessions_?
They store our generated cookies and maintains the state between http requests.

2. What does bcrypt do to help us store passwords in a secure manner.
bcrypt takes our user generated password, then encrypts it and turns it into a hash. The more "salt" that is added, the harder it is to crack the password. Salt protects against rainbow table attacks.

3. What does bcrypt do to slow down attackers?
A timer is placed when an attacker is attempting to brute force his/her way into the site. This intentional delay will slow down the attacker.

4. What are the three parts of the JSON Web Token?
The header
The payload
The signature
