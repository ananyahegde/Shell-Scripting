### Understanding what system does during a shell session. 

When we log on to the shell session, the bash program starts, and reads a series of configuration scripts called *startup files*.This sets up the *environment* (contains generic informations such as PATH, user name, etc). <br> 
The environment first established is a default environment, shared by all users. This is followed by a process of creating environment for individual users. 

### Shell session
Login session - session started by loging in with user name and password 
Non-login session - not prompted to log in. Such as accessing through GUI terminal. 

### Aliases and Shell Functions
Aliases creates a new command as short-hand command to an already existing one. 
Shell functions are much complex, and can be thought as creating a command consisting of multiple commands. 

Both can be created in a bash script or directly in command line. But Aliases and Shell Functions created in a command line will only exist till you terminate the session. 

