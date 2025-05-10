# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**


![image](https://github.com/user-attachments/assets/888ef6e4-7042-4e5e-8ad6-a377a546e3e4)


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:** 


![image](https://github.com/user-attachments/assets/85116140-23a7-46c9-b648-4cf2d26c04aa)


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/92319599-fe74-41c2-9890-70a6dbd56345)


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/66f08e16-9679-4552-8143-401d92ddc56f)

### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/fad8ebac-9edd-452f-953d-41f38bd569d7)


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**


![image](https://github.com/user-attachments/assets/c7ecaccb-001f-4907-96f1-5babb764ebde)


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**


![image](https://github.com/user-attachments/assets/a27d4570-f3ee-4796-98c1-8b34585e4efb)


### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/b94c47f4-839f-4457-b236-52b92a2aa293)


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**


![image](https://github.com/user-attachments/assets/f3344a0a-594c-4431-8e69-eaf6a727db5c)

### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**


![image](https://github.com/user-attachments/assets/41795302-a7bf-4e59-aa2d-7f8ab9c797db)


### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**


![image](https://github.com/user-attachments/assets/82ae5c36-916b-4c05-be98-2535a8587998)

### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/2038710a-f451-42e6-a318-4202b0e02f8c)

### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/463158ab-8b2f-4084-ad0d-1dbfac163ef8)


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**


![image](https://github.com/user-attachments/assets/0a132d13-9680-44e8-a3ce-27566fc16e96)


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**


![image](https://github.com/user-attachments/assets/2decb83e-8705-4c30-b1f9-884f6e206203)


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**


![image](https://github.com/user-attachments/assets/351c3886-6e34-4f76-afba-4c496a5dc93e)


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/1ccc5d56-8311-459c-9bed-b5252d86322a)


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**


![image](https://github.com/user-attachments/assets/95c6c526-d58b-46bb-b8c8-eb0a9fc2a38a)


### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/64c6dec1-a4f9-4ec1-94a1-905307161753)


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**


![image](https://github.com/user-attachments/assets/bdde318b-1439-433c-9f7b-866f6bfd39c2)


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**


![image](https://github.com/user-attachments/assets/4fc5123b-b2cc-4cb5-9a65-6f76c24e69d9)




### 22. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**


![image](https://github.com/user-attachments/assets/dd64b2c8-f9a7-44c8-8e7f-800b0991656a)


### 23. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**


![image](https://github.com/user-attachments/assets/1d61c204-5c21-468b-83ba-3e015758406d)


### 24. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/4284f7d5-bb2b-4c18-8da2-032b447255df)

### 25. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**


![image](https://github.com/user-attachments/assets/5ba3240e-905a-4986-8431-8ecb889dfe27)

### 26. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**


![image](https://github.com/user-attachments/assets/6f96c040-d8be-442b-8aaf-f2f147232218)


### 27. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**


![image](https://github.com/user-attachments/assets/5031daf2-b182-494c-b69a-accbbfcf8813)


### 28. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**


![image](https://github.com/user-attachments/assets/5a4b8fcc-dcb8-4320-aad0-80a2000b3244)


### 29. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/ac427826-a23e-441f-a92e-d05967bed286)


## Result
All basic and advanced operations were successfully performed through appropriate Linux commands, with the system responding accurately to each, confirming correct execution and expected behavior, thereby demonstrating the effectiveness and reliability of the Linux command-line interface for comprehensive system management.
