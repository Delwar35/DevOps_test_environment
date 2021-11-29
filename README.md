**Hello**
# DevOps Intro
# Development Env

-Install Vagrant
-Install Ruby

```

```
commands

**Linux:**
`sudo apt-get install <commands/packages>` - install <commands/packages>
`systemclt status <name>` - shows status of <name>
`uname` - who am i - info about os
`uname -a` - who am i (info about os more detail then uname)
`pwd` - current loction 
`ls`  - lis directory
`la -a`  - list all directory 
`cp <filename><destination>`  - copy file
`mv <filename><destination>`  - cut or rename
`touch <filename>`  - create file 
`mkdir <foldername>`  - create folder
`cd <destination>`  - how to navigate
`cd ..`   - return step back 
`rm  -rf <foldername>`  - delete file
`rf <foldername>`  - focus delete file
`top`  - shows all files running
`kill <process id>`  - stop a process (can kill multiple process by adding multiple process id and seperate with space)

**File permission:**
`r`  - read
`w`  - write
`x`  - exacutable 
`ll`  - to check file permission
`d`  - is a directory
`chmod <filename>`  - change permission of <filename>

 
**Vagrant:**
vagrant up  - will create and run the VM
vagrant destroy  - will stop and destroy the vm
vagrant reload  - will update the vm (if it doesn't work do destroy then up)
vagrant ssh  - to get into the vm when it is running
vagrant status  - shows the status of vm (if it's running or not)

**Filters:**
`cat <file>`  - reads text in the file line by line
`head <-number of lines(n)> <file>`   - reads the first n lines in <file>
`tail <-number of lines(n)> <file>`   - reads the last n lines in <file>

**Piping**
Pipe is used to combine two or more commands (using `|`), and in this, the output of one command acts as input to another command

```
command_1 | command_2 | command_3 | .... | command_N 
```


