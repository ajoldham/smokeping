![logo](https://raw.githubusercontent.com/ajoldham/smokeping/master/logo.png)

Docker SmokePing
================

This installs SmokePing monitoring on Linux Debian with a working config monitoring multiple web sites and DNS servers.

Copy with:
```php
git clone https://github.com/ajoldham/smokeping
```

Build with:
```php
docker build -t smokeping .
```

Tweak the ./config files if desired and run with:
```php
docker-compose up
```

Access SmokePing with:
```php
http://127.0.0.1:8888/
```

Credit to Docker SmokePing source used from here:
https://github.com/dperson/smokeping