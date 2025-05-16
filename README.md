[# 19CS416-CS-Ex-3-Linux-Commands

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

![image](https://github.com/user-attachments/assets/a492afb0-15bf-46d9-94f5-a84f1366da5c)


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**

![image](https://github.com/user-attachments/assets/49b1d86b-ba5b-429c-88c4-ccf7f27bb2e8)


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/2e9c15c2-b0ec-4131-9385-b7fdcbbd9b21)


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/99828bb6-30fc-4b9b-84f9-6b1ecbed9eab)


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/77d686ad-f8c9-4e43-b138-bfd935fc91e3)


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**

![image](https://github.com/user-attachments/assets/e9a8fb48-c08f-423e-9c55-669d359f3daf)


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

![image](https://github.com/user-attachments/assets/eeff02c4-bba6-429c-849a-8a8c1e63312d)


### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/cbfdbbe6-7411-4a0e-8e03-f57cb451cc04)


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

![image](https://github.com/user-attachments/assets/623a10a4-6c98-496c-aa4c-64cb1ededda8)


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

![image](https://github.com/user-attachments/assets/48bb80c7-13b2-4620-a9d5-a4cf1594bae2)

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**

![image](https://github.com/user-attachments/assets/e316cd54-5cde-42b8-b5c2-b3fc007c30ba)


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/8976cefb-2848-4eae-937c-89e201e0c655)


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/e39135b8-6c9f-4a8a-a093-9e91de8615f9)


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**

![image](https://github.com/user-attachments/assets/9b093a3b-80c4-452c-bf1e-5ef98f74002c)


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**

![image](https://github.com/user-attachments/assets/c23654ed-e846-42ed-aa73-967356ceff70)



### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**


![image](https://github.com/user-attachments/assets/ab38c17e-4a36-4a41-b14d-9df49d1f1c6d)



### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/6989a5d5-f604-4baa-bb5f-e59f36c73b90)


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**


![image](https://github.com/user-attachments/assets/d1f71f09-0ff2-4977-91ec-70b4c99b052f)


### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/9183cdcb-eda0-4302-8185-2ea287c9cadb)


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**


![image](https://github.com/user-attachments/assets/9389e45c-5b88-4569-a69f-7f151e86ac97)

### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**


![image](https://github.com/user-attachments/assets/1507c86f-04e0-4769-8e1b-f2381b38d0d5)


### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**


![image](https://github.com/user-attachments/assets/9bc691b5-f366-410f-b69d-ee414d6dd3ac)

### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**

![image](https://github.com/user-attachments/assets/007b7185-82a1-41e2-8e13-3ce0635b672a)


### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**


![image](https://github.com/user-attachments/assets/51f416f4-9d27-44cd-8b86-eac33cbd546c)

### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**


![image](https://github.com/user-attachments/assets/1847912b-fd5e-48b7-828b-482be4d5d240)

### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**

![image](https://github.com/user-attachments/assets/bdd78975-e147-4025-8f6f-dfed9ff9050f)

### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**

![image](https://github.com/user-attachments/assets/00ef0039-f5ce-4860-9df9-77561ce2535d)



### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**

![image](https://github.com/user-attachments/assets/5b4251a0-836f-4fdd-a2b7-95477e90d01c)

### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**

![image](https://github.com/user-attachments/assets/b61c5a2c-e657-407b-904c-042b21741ea5)


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/020a3434-636b-4552-8173-26576164caeb)


## Result
Successfully executed the linux commands
