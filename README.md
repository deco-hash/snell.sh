# docker
## https://github.com/primovist/snell-docker
## https://hub.docker.com/repository/docker/primovist/snell-docker

Debian & Ubuntu

```
wget --no-check-certificate -O snell.sh https://raw.githubusercontent.com/primovist/snell.sh/master/snell.sh
chmod +x snell.sh
./snell.sh
```

Centos & RedHat

```
wget --no-check-certificate -O snell.sh https://raw.githubusercontent.com/primovist/snell.sh/master/snell.centos.sh
chmod +x snell.sh
./snell.sh
```

nano /etc/snell/snell-server.conf
systemctl restart snell
```


```
systemctl status snell
```


```
wget --no-check-certificate -O uninstall-snell.sh https://raw.githubusercontent.com/primovist/snell.sh/master/uninstall-snell.sh
chmod +x uninstall-snell.sh
./uninstall-snell.sh
```
