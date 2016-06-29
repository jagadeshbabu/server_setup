## EC2 Server Setup:

1. Login as root using the keypairs

2. Setup the necessary users and their passwords with

```
$ sudo adduser USERNAME
$ sudo passwd USERNAME
```

3. Edit /etc/ssh/sshd_config setting

```
PasswordAuthentication yes
```

4. Restart the ssh daemon with

```
$ sudo service ssh restart
```
