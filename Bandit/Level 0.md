# Level 0 ✔

**Goal:**<br>
Log into the game using SSH. Once logged in, go to the Level 1 page to find out how to beat Level 1.<br>

**SSH Information:**<br>
Host: `bandit.labs.overthewire.org`<br>
Port: `2220`<br>

**Login SSH:**<br>
Username: `bandit0`<br>
Password: `bandit0`<br>

## Write Up:<br>

In this, we just connect remotely to their server by using "ssh" with above username & password<br>
Use `man ssh` for more details<br>

Syntax: `ssh user@host -l username -p port`<br>

With<br>
-l: choose user to login<br>
-p: port to connect<br>


## Solution:<br>
Command: `ssh  bandit.labs.overthewire.org -l bandit0 -p 2220`
