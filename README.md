# Anon-Pass
A protocol and system for subscription services, allowing users to authenticate anonymously.

index.html - basic login, register and reup

index2.html - same as index.html, used to show 'repeated login' instance

web_service_login.html - to gain access to web service

Client messages - browser console
Server messages - terminal

Web socket for communication (install pywebsocket python library)

Enter mod_pywebsocket folder and run:

sudo python standalone.py -p 9998 -w ../example/

In Example folder echo_wsh.py script exists.
Modify this script to listen and send messages from the server.