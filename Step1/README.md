# Meteor.js Project - Code Review.

## Security
Http post request in File client/main.js, line # 34 sends the password in the URL.
* Passwords shouldn't be sent in the URL, it's possible that browser plugins, proxies record the visited urls and password can be compromised.
* For client - server interaction it is better to use a client key hash which can be sent across in the headers with each request.
* Changes made in code to incorporate the same.

## Improvements
* client/main.js, line #23 - Record the count of users who have logged in. Check for user id before sending the request.
* client/main.js, line #19 - I'm not sure about how this works in Meteor, but a getter / setter should be used to access the variable. 