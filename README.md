
# Cloud Security Lab 1: Linux Commands Study

## Introduction to Linux

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

![image](https://github.com/user-attachments/assets/cf38bd8d-bb16-42a9-88d0-e475e30da671)


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**

![image](https://github.com/user-attachments/assets/02e68722-3697-4dbf-93a1-4907d4e6a71c)


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/c7b5422a-1d5f-44ce-81ed-244a8fda0cf6)


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/77885f88-94b0-4f29-a270-4f94035283a8)


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/1abcda7d-3ecd-4f28-90ae-0292dc58eaf7)


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**

![image](https://github.com/user-attachments/assets/be60bce1-d69c-4ef6-baba-67383fc60cff)


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

![image](https://github.com/user-attachments/assets/fca1f425-e866-45d4-a415-48919e91a9b7)


### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/97577254-29ea-4b61-b06c-a42e119b4048)


### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

![image](https://github.com/user-attachments/assets/b9f7854c-21e1-49b3-9518-87225a6e77d9)


### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

![image](https://github.com/user-attachments/assets/6838b364-2fdc-414a-8742-c53bf870425b)


### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**

![image](https://github.com/user-attachments/assets/9b8c9bbc-c115-4002-a6c6-830dcaf2658a)


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/a20a6a70-eca5-4c1e-9ca9-3f9db34a32f9)


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/9c949bf0-dbd6-48bf-948f-aef5f53d9fe6)


### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**

![image](https://github.com/user-attachments/assets/0cccfbb9-ab49-495f-b614-34d272d3f1ca)


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**

![image](https://github.com/user-attachments/assets/9dd32cc1-015f-4ede-a502-19494e55af20)


### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**

![image](https://github.com/user-attachments/assets/f8dd43d9-48e3-4d17-9c0a-a2384f49d723)


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/b88a50d4-0c30-43bf-9abc-418fa1fa0734)


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**

![image](https://github.com/user-attachments/assets/9dbb3c1c-38b4-47f6-9c62-c478a1539999)


### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/3ab7f333-b985-49e9-b19f-e4daefb8225f)


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**

![image](https://github.com/user-attachments/assets/a9726a06-b562-487a-b35f-1d059ff30414)


### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**

![image](https://github.com/user-attachments/assets/fdf6b89c-1b24-404a-82f1-03c47a78d4d3)


### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**

![image](https://github.com/user-attachments/assets/9f1b0dc4-fb80-4fb8-b247-319018d53b87)


### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**

![image](https://github.com/user-attachments/assets/76317215-ea93-4e67-b06d-c6bbaa4690b9)


### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**

![image](https://github.com/user-attachments/assets/d68c9133-e607-4e4d-80ee-1cbad839699f)


### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**

![image](https://github.com/user-attachments/assets/7024d5b3-cf0b-4146-8d46-a75c34c1fc41)


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**

![image](https://github.com/user-attachments/assets/2690490f-21d2-438f-ae4a-1e40c42bd3c8)


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**

![image](https://github.com/user-attachments/assets/22aa6353-79d7-4bce-a561-42cfca4a6511)


### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**

![image](https://github.com/user-attachments/assets/089e6653-6b7d-4fff-8ec7-b424e07f9fe9)


### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```


## Result

Linux commands are executed in the linux terminal successfully.
