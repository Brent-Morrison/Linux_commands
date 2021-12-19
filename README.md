# Linux_commands
A personal cheat sheet for Bash. 

Now that 

I'll put the frequent ones here in the README.  Others can go into dedicated files.

## Text files

<br>

| Action | Command |  
| :----- |:------- |  
| View file | ```cat <file_name>``` |  
| View permissions | ```ls -l <file_name>``` | 
| Set permission | ```sudo chmod 774 <file_name>```[^1] | 
| Find location of file | ```sudo find / -name <file_name>``` |  
| Delete file      | ```rm <file_name>``` |  
  
[^1]: This assigns rights as follows:  
  
| Rights | Owner | Group | Others |  
| :---- | :---: | :---: | :----: |  
| Read | 4 | 4 | 4 |  
| Write | 2 | 2 | 0 |  
| Execute | 1 | 1 | 0 |  
| TOTAL | **7** | **7** | **4** |  