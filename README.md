# Simple web

## Setup

### Debian and derivatives

```
sudo apt install apache2
sudo systemctl disable --now apache2
```

## Running

### Debian and derivatives

```
/usr/sbin/apache2 -D FOREGROUND -d .
```

```
curl http://localhost:8000/test
```
