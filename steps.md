## EC2 Server Setup:

- Login as root using the keypairs

- Setup the necessary users and their passwords with

```
$ sudo adduser USERNAME
$ sudo passwd USERNAME
```

- Edit /etc/ssh/sshd_config setting

```
PasswordAuthentication yes
```

- Restart the ssh daemon with

```
$ sudo service ssh restart
```
