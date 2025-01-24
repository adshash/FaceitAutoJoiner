# FaceitAutoJoiner
## A small app to auto connect to Faceit Servers

### How it works:
1.) A python script will interface with faceit in order to obtain the connection code ("connect 123.456.789").
2.) A cfg file that has been created by the application (named "AutoJoiner") will then be created/rewritten to contain this code.
3.) CS will open and execute this cfg file to connect to the server.
4.) The program immediately terminates in order to avoid conflicts with faceit AC.

### Why not Use Repeek? 
The repeek auto-connect feature connects directly through a browser command, potentially leading to fps issues. This program is aimed to mimic real human-computer interaction, reducing an effects to FPS. 
