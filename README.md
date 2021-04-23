# TalesFromTheKrypt

This model is a Wordpress plugin written in PHP designed to act as ransomware. This program only affects cosmetic files on the site, and should not hinder fundamental function in any way. It utilizes PKI to conduct encryption and decryption operations. It functions as a top-down worm to effectively target every file that matches its criteria. 
The model also plants two PHP script backdoors. One is the infamous P0wny-shell (https://github.com/flozz/p0wny-shell) to be served on the site, and the other is a simple reverse shell created by PentestMonkey (http://pentestmonkey.net/tools/web-shells/php-reverse-shell).

Tested on Linux (CentOS7, Ubuntu18 Server) systems. Theoretically should work on Windows systems that have PHP enabled, but tests have not been conducted. 

This piece of software is to be used strictly for educational purposes within a controlled, authorized, and isolated environment. Use at your own risk. You have been warned.
