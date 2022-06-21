### Filesystem and File Permissions

- A newly created Bash Scripting file <code>.sh</code> cannot be executed until some certain permissioons are given 

- That's why we need to know how folders or directories and files are permitted for certain funtions on Linux

- The Filesystem determines control over data that is stored in a directory or file as Linux makes no difference between the files and directories

- There are some sort of files and directories as <code>Ordinary Files</code>, those contain data, text files, images, files that consist of most likely the userdata, <code>Special Files</code>, those have access to hardware devices, mostly the files of root directory and <code>Directories</code>, those contain both ordinary and special files

- There are 3 types of Permissions associated with any file i.e. <code>Read(r)</code>, <code>Write(w)</code> and <code>Execute(x)</code>

- As per the names of aboove permissions, one can say <code>r</code> permission allows to view file content not to modify it, <code>w</code> allows to write or modify the content inside the file and <code>x</code> permits to execute or run any programming or script file that is made in that purpose

- If we create a Bash Script file using <code>touch</code> cmd or any text editor and analyse the permissions using <code>ls -l</code> that are given default, we would find that there is no execution permission given yet, like [this](https://github.com/ritukanta/Bash/blob/03/screenshot.png)

- To make it executable, we use <code>chmod +x FileName</code>

- After changing permissions to make it executable, you can run ur bash script file as:
```
./filename.sh
```
- If we change permissions and run this [script file](https://github.com/ritukanta/Bash/blob/02/02.sh), the result will be [this](https://github.com/ritukanta/Bash/blob/03/ss-2.png)