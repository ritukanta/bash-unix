### Bash Scripting

- Bash Scripting is a powerful part of system administration and development used at an extreme level.

- It is used by the System Administrators, Network Engineers, Developers, Scientists, and everyone who use Linux/Unix operating system. They use Bash for system administration, data crunching, web application deployment, automated backups, creating custom scripts for various pages, etc.

- A bash shell script is a plain text file but plain random texts can't be written, containing a set of various commands that we usually use on the command line

- It automates those repetative commands on Linux OS

### Create and a Bash Script/ .sh

- To create a .sh file, change to Desktop or ur desired directory and open the default command line. For Windows, u can use any text editor such as VSCode, Sublime text etc

- Then create a file with extension <code>.sh</code> using </code>touch</code> cmd on Linux or any other text editor i.e.
```
touch hello.sh
```

- Now a bash script is there, to edit that file, enetr: <code>nano hello.sh</code> on Linux distros or an editor on Windows

- As we didn't add any texts or command line text in the hello.sh file, we need to add some

- For a standard practice, each bash or Linux user writes <code>#! /usr/bin/bash</code> in very first line of any .sh file. Where <code>#!</code> is known as <code>SheBang</code> and the rest(/usr/bin/bash) is the location path of bash on ur OS which was known by <code>which bash</code> command previously

- Bash uses # to comment any line of texts i.e. those lines starts with # won't be executed or printed and it uses <code>echo</code> with double quotes to print the output