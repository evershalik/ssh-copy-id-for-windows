# ssh-copy-id-for-windows

To do ssh-copy-id in your windows system, you can use the below cmd:
```bash
cat ~/.ssh/id_rsa.pub | ssh user@123.45.67.89 "cat >> ~/.ssh/authorized_keys" 
```

> **NOTE:** `user` is your username, and replace `123.45.67.89` with your machine/host/VPS's IP address.
