Small web app built using MongoDB, Express, and React.

Allows for the registration of users, and then for registered users to add contacts for the app to remember. 
(It's essentially the contacts app you have in your phone)
 
Registration is handled using bcrypt for password hashing + jwt to handle transport of user data. 
We are also using express-validator for simple validation of form fields. 
Mongoose is used to handle database abstraction in our server. 
