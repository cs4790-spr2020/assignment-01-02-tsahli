# BlabberApp

BlabberApp a Twitter-like .NETcore class project

## SSH Tunneling

SSH tunneling or port forwarding is a technique for viewing a remote web server on your local machine.  It makes it look like the web server is running locally when actually it is running in your account on the class server.  Here is detailed information: [SSH Port Forwarding](https://www.ssh.com/ssh/tunneling/example).  Here is an example of my personal port fowarding command:

`ssh 64.225.37.60 -L 5041:localhost:5041 -N`
