Clone repository
```
git clone git@github.com:kovaszab/raspy.git
```

Copy your shh keys to the raspberry pi
```
ssh-copy-id -i ~/.ssh/id_rsa.pub user@0.0.0.0
```

Add 'user@host' to your /etc/hosts file with the ip of your raspberry pi
```
0.0.0.0 host
```

Edit Line 12 of the Bash script to match your user@host
```
remote_host='arc@qpi'
```