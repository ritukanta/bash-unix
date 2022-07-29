## Bash Comments

- Comments are the necessary part of any programming language, used to define the usage or function any code we write.

- Usually comments are not executed but help in readability of the code.

- Categorized into two types of comments, alike other programming language;

1. Single Line Comments
1. Multi-Line Comments

### Single-Line Comments

- First off, **Hash(#)** is used at the starting of a line to make it single line comment.

> Here's an example
```Bash
#! /usr/bin/bash

# This is a single line comment;
# This won't be executed!
echo "Yikes! a Very good evering"
```

### Multi-Line Comments

- There are **two ways** to insert multi-line comments in bash scripts;

1. We can write multi-line comments in bash scripting by enclosing the comments between **<<COMMENT** and **COMMENT** .

1. We can also write multi-line comments by enclosing the comments between (<code>: '</code>) and single quote (<code>'</code>) .

> Example;
```Bash
#! /usr/bin/bash

<<COMMENTS  
    This is the first comment  
    This is the second comment  
    This is the third comment  
COMMENTS   
echo "Hello, World!"  




: '  
This is the first comment  
This is the second comment  
This is the third comment  
'
echo "Hello, World!"
```