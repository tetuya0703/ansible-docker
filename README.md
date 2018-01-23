# ansible-docker

# docker host setting
```
export DOCKER_HOST="tcp://＊＊＊。＊＊＊。＊＊＊。＊＊＊:2375"
```

# firewalld setting
firewall-cmd --permanent --zone=public --add-port=2375/tcp
