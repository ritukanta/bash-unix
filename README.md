## Variables

- Variables are the containers which contain some data we write.

- There are 2 types of variables; 
1. System Vars
2. User Defined Vars

- System Vars are already defined by ur Operating System mainly in Linux OS, usually written in Upper cases.

- User defined vars can be created by you, the user.

> Examples;
```Bash
#! /usr/bin/bash

#sys vars
echo $Bash
# this will show ur Bash path on the OS
echo $HOME
# this will show ur desktop home path
echo $PWD
# this will show the present working directory


#user defined vars
name=rituK
echo my name is $name

place=India
echo I am from $place
# u can name a user define on ur own
# user defined vars should never start with any integer
# always should start with alphabets
10=value
echo the value is $value
# the above will never be executed!
```