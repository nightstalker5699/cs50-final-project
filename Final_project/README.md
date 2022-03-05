# MakeTheDogHappy
#### Video Demo: (https://youtu.be/xcLHVQvV6vM)
#### description:

# register
## register.py
 ![photo](https://github.com/nightstalker5699/cs50-final-project/blob/04a0ad7b2e6f54e9b234ef3126407e0a58a70f11/readme%20images/register/Screenshot%202022-03-05%20195340.png)
 first we check if user got here by get or post 
 if get then the register page will popup 
 else we create a class that have  all flask-wtform field and we assign that class to local variable called form
 ![photo](https://github.com/nightstalker5699/cs50-final-project/blob/c2c345c57abe95552020e31024ed93ff99beb242/readme%20images/first.png)
 after that we check for validation if it didn't validate right then user will get apology page (pset 9 for used to display user error)
 else we check for password and confirmation to be same if not you get apology :D
 after that we put your information in the database using sqlite3 and generate hash of the password not the password itself for security reasons
 ![photo](https://github.com/nightstalker5699/cs50-final-project/blob/fa95bdcb694c51829cecd0c9d7b3655f12691a89/readme%20images/register/Screenshot%202022-03-05%20195400.png)
 # login
 ![photo](https://github.com/nightstalker5699/cs50-final-project/blob/6ca58106c2673d0da8ca04448c769e65bda2bfcc/readme%20images/login/Screenshot%202022-03-05%20195449.png)
 same as register with get and post 
 first we the list of all users thave account on the site then we iterate on the list until we found username that matches the user typed then we use the check password hash function to dehash the password and if the password is same then it will return true else return false
 if we found the username and password then the user will be redirected to the home page with his session id 
![photo](https://github.com/nightstalker5699/cs50-final-project/blob/6ca58106c2673d0da8ca04448c769e65bda2bfcc/readme%20images/login/Screenshot%202022-03-05%20195508.png)
