## Set up

If you are using this on the Yoobee Servers. 
We are behind a proxy so you will need to set up a config.inc.php file outside of the public html

paste these 2 lines 

define('YOOBEE_USERNAME', '');
define('YOOBEE_PASSWORD', '');

Enter your username and password you use to log onto the computers

## If you are using this at home/live

Go to apple-search.php

Remove lines:
3 and 4 (the line which includes your config file)
21 - 25 (the lines which uses our config data to get passed the proxy)