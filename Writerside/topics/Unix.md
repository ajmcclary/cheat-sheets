# Unix

## Basic Commands

**List files in a directory**
```bash
ls
```

**List all files, including hidden ones**
```bash
ls -a
```

**Change directory**
```bash
cd <directory_path>
```

**Print the current working directory**
```bash
pwd
```

**Create a new directory**
```bash
mkdir <directory_name>
```

**Remove a directory**
```bash
rmdir <directory_name>
```

**Remove a file**
```bash
rm <file_name>
```

**Copy files or directories**
```bash
cp <source> <destination>
```

**Move or rename files or directories**
```bash
mv <source> <destination>
```

## File & Directory Permissions

**View file permissions**
```bash
ls -l
```

**Change file permissions**
```bash
chmod <permissions> <file_name>
```

**Change file owner**
```bash
chown <owner> <file_name>
```

## File Viewing & Editing

**View the contents of a file**
```bash
cat <file_name>
```

**View file with paging**
```bash
less <file_name>
```

**Display the first 10 lines of a file**
```bash
head <file_name>
```

**Display the last 10 lines of a file**
```bash
tail <file_name>
```

**Edit a file with nano editor**
```bash
nano <file_name>
```

## Process Management

**Display currently running processes**
```bash
ps
```

**Kill a process by PID**
```bash
kill <pid>
```

**Force kill a process**
```bash
kill -9 <pid>
```

**Check system resource usage**
```bash
top
```

## Networking

**Check network configuration**
```bash
ifconfig
```

**Ping a server to check connectivity**
```bash
ping <hostname_or_ip>
```

**Check open ports**
```bash
netstat -tuln
```

## Miscellaneous

**Check system uptime**
```bash
uptime
```

**View disk usage**
```bash
df -h
```

**Search for files**
```bash
find <directory> -name <file_name>
```

**Search for text in a file**
```bash
grep "<text>" <file_name>
```
