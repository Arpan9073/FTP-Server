# FTP-Server
Developed a socket-based FTP server supporting multiple clients with login/sign up functionality, file handling, and threading for concurrent access.

#### Setup & Execution
1. First run the server.py script *(Note: need python 3.13.3 or higher installed)*.
2. Then run the client.py code.
> **Note:** If the client and server are running on the same machine, set the host to `localhost`/`127.0.0.1`. If they are on different machines within a network, update the host to the server's LAN IP (e.g., `192.168.x.x`).
3. Then you need to *log in* or *sign in* if you are using first time then you can start executing your command.
4. **Commands:** After login you can start executing your command, just write down your command and press enter *(enter valid commands only)*. Below there are the list of commands- 
	1. `list`: List all the files that are in the server.
	2. `download`: To download a file from the server. It will list all the files first, then you need to enter the file name you want to download and press enter *(Note: wrong file name will give you a warning and you have to re-execute the command)*.
	3. `upload`: To upload a file into the server. First it will list all the files in the particular folder, then it will ask to enter the file name you want to upload and press enter *(Note: wrong file name will give you a warning and you have to re-execute the command)*.
	4. `delete`: To delete a file from the server. It will list all the files first, then you need to enter the file name you want to delete from the server and press enter *(Note: wrong file name will give you a warning and you have to re-execute the command)*.
	5. `close`: It will close the connection.
