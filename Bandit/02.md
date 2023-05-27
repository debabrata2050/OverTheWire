# Level 1 - Level 2 :heavy_check_mark:

**Goal:**<br>
The password for the next level is stored in a file called - located in the home directory<br>

**SSH Information:**<br>
Host: `bandit.labs.overthewire.org`<br>
Port: `2220`<br>

**Login SSH:**<br>
Username: `bandit1`<br>
Password: `NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL`<br>

## Write Up:<br>

In this, a "dashed" filename must be read.<br>
The "-" symbol often designates the command's parameter.<br>
As a result, we must employ a unique syntax to distinguish between the two.<br>

Syntax: `cat ./{-filename}` or `cat < {-filename}`<br>

## Solution:<br>
Command: `cat ./-`<br>

## Next Level: :next_track_button:<br>
:key: Password: <b>rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi</b>
