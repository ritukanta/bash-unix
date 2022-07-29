## Relative vs. Absolute Path

- Before creating a Bash script, u should be well aware of the shell navigation and the difference between the **relative** and **absolute** path for an intended file.

### What is a Path?

- A **path** to a file is merged form of **slash(/)** and alpha-numeric characters.

- It determines the unique location of a file directory in an OS file system.

#### Absolute Path

- An **Absolute** Path is a full path specifying the location of a file or directory from the root directory or start of the actual filesystem.

- An **Absolute path** of any directory or file always starts with a slash(<code>/</code>) representing the directory root. Each slash(<code>/</code>) separates the directories followed by.

> For an example;
```Bash
/c/Users/ritukanta/Desktop/Bash/04
```

- All directories names in a absolute path are written in an hierarchy order, the most parent directory name is written on the left side(/c here) and the target directory's name is written on the right side(/04 here).

- The absolute path of any directory can be known using <code>pwd</code> command.
```Bash
$ pwd
/c/Users/RITUKANTA/Desktop/Bash/04
```

#### Relative Path

- The **relative** path of a file is its location relative to the current working directory. It never starts with a slash (<code>/</code>). It begins with the ongoing work directory.

> For example;
```Bash
..Desktop/Bash/04
```