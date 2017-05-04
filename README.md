# chat_program
This repo consist of an implementation of server-client model with the server having abiltiy to handle multiple client simultaneously.

The server is to be executed in python3 and does not have a GUI with it, where as the client has an associated GUI built using Tkinter and also has the capability to send multimedia files and also supports unicast/multicast/broadcast.

Server side will also maintain a database to authorise/register user in the application hence to run the program, the directory conataing "server.py" must also have "database.txt".

to use the server side, on terminal do:
~~~
python3 server.py <port number>
~~~

to use client side, do
~~~
python client.py
~~~
after this GUI would appear which is simple enough to follow
