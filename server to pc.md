## SSH connection

```
ssh username@server_ip
# fill in password
```

## Transferring folders from personal pc to server with tar

```
# In your pc:
tar -czf folder_name.tar.gz folder_name

#transfer to the server:
scp folder_name.tar.gz username@server_ip:/home/username/
#or use flashdisk

# In the server:
tar -xzf folder_name.tar.gz
```

nexts step:
```
#just go in the folder
cd folder_name
ls
```
