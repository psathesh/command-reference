
## Apache Basic Commands on Mac


Output a short summary of available command line options
```
sudo apachectl -h
```

Uses the specific file configuration on startup
```
sudo apachectl -f ~/conf/httpd.conf
```

Signal command to start stop and restart apache
```
sudo apachectl -k restart
sudo apachectl -k start
sudo apachectl -k stop
```

Run syntax tests for configuration files
```
sudo apachectl -t
sudo apachectl configtest
```

Print the version and build parameters
```
sudo apachectl -V
```

Print the current running configuration file path
```
sudo apachectl -V | grep SERVER_CONFIG_FILE
```


Reference
https://httpd.apache.org/docs/2.4/programs/httpd.html

