# Key-Util

Simple script used to create and transfer keys between hosts to faciliate passwordless login. I wrote this for use with Ansible. 

Generating a key using key-util:

    key-util -g [ ip address| hostname ] 

Send key to host:

    Key-util -s [ ip address | host name ]
    
Remove a key from a host:
    
    key-util -r [ ip | hostname ] 

Test connecting to a host after key was sent:

    key-util -t [ ip | hostname ] 
    
 Generate keys, send keys and test login:
 
     key-util -t [ ip | hostname ] 
    
