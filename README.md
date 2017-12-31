# Secure User Login And Authentication Class
 
 This is a user authentication and login class that utilizes php sessions and creates
 a secure session for storing the user's login status and any other session data.
 It also allows for persistent login support by utilizing session cookies.
 
  It includes a vigorous user password encryption method as well.
 
 Requires PHP5 >= 5.1 
 
 #### license     
		http://creativecommons.org/licenses/MIT/ MIT
 #### category    
		authentication
 #### package     
		Secure User Sessions
 #### author      
		David Miles <david@amereservant.com>
 #### orig-link   
		https://github.com/amereservant/Secure-User-Login-And-Authentication-Class
 #### orig-link   
		https://github.com/VarolOkan/Secure-User-Login-And-Authentication-Class
 #### version     
		1.1
 #### since      
		1.0 (January 14, 2011)
 #### updated     
		Dec 31 2017 Varol Okan

Improved slightly to work with sample LoginPage from

## usage :

### Login: 
http://<server>/path/to/script/user.class.php?type=login&username=me&password=secret123&remember=true

### Logout:
http://<server>/path/to/script/user.class.php?type=logout

### Check if logged in:
http://<server>/path/to/script/user.class.php?type=check

### Register:
http://<server>/path/to/script/user.class.php?type=login&username=me&password=secret123&email=test@test.com

### Forgot password ( not yet implemented ):
http://<server>/path/to/script/user.class.php?type=forgot&email=test@test.com

### Create new User database:
http://<server>/path/to/script/user.class.php?type=newDB

### Code playground:
https://www.astranos.org/MiyamotoMusashi/BattleGround.php?course=7
-- YouTube link goes here --


