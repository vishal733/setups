```
sudo adduser vishal
```

## ssh-related

https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys-2

```
ssh-keygen -t ed25519
ssh-copy-id vishal@your_server_address

# Disable password-based SSH authentication
sudo nano /etc/ssh/sshd_config

```
