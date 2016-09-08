## Set up

If you are using this on the Yoobee Servers. <br />
We are behind a proxy so you will need to set up a config.inc.php file outside of the public html<br />

paste these 2 lines 

define('YOOBEE_USERNAME', '');<br />
define('YOOBEE_PASSWORD', '');<br />

Enter your username and password you use to log onto the computers<br />

## If you are using this at home/live

Go to apple-search.php<br />

Remove lines:<br />
3 and 4 (the line which includes your config file)<br />
21 - 25 (the lines which uses our config data to get passed the proxy)<br />