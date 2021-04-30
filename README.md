# ssh-test

This is my repo to demonstrate using git with ssh

1) Setting up ssh for Github repo

: generate a pair of keys (public key - private key)\
: and associate the SSH key to GitHub account

`ssh-keygen`

-> this will create new 2 files, which are like **filename** and **filename.pub**

-> copy content of **filename.pub** file and paste to Github account

2) execute the following 2 commands every time setting up ssh connection with Github

`` eval `ssh-agent` ``

`ssh-add <filename>`

Eg: `ssh-add ~/ssh\ keys\vdhuy`
