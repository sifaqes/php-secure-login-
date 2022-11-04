PHP Secure Login Secure Login: Licencia gnu.org copia de siphax 
==============
Includ js - bootstrap

A version of the WikiHow page is saved with this project as 'php-secure-login.odt'.

The idea is to modify the code so that it forms a module that can easily be plugged into other PHP projects requiring login functionality.

When it's done, users will be able to select from a variety of configuration options such as:

* Connect via http or https
* Specify database connection details
* Elect whether all users should be allowed to register or whether only certain types of users should be able to do registrations (i.e. register other users)

You'll need Apache, mySQL and PHP5.3.x installed and working.  On Windows and Mac, an XAMPP installation will be fine.

You'll also need to create a database called 'secure_login'.  When you've done that you need to create a user with just SELECT, UPDATE and DELETE privileges on the 'secure_login' database.  The user's name and password are given in the psl-config.php file.  If you're not intending to contribute, you can choose whatever login details you want, but you'll have to change the psl-config.php file to match your own details.

The code to create and populate the necessary tables is included in the 'secure_login.sql' file.  It populates the members table with a single user with the following details:

Username	: test_user 
Email		: test@example.com 
Password	: 6ZaxN2Vzm9NUJT2y

The registration page is now implemented, so you can register as many users as you like.  However you may still need the test_user for testing purposes in the future when we come to adding roles to users.

I'm happy to receive any suggestions (siphaxzer@gmail.com).  And if anyone would like to help...

