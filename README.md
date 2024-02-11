# kali-linux

## Update
```
sudo apt update
sudo apt -y dist-upgrade
sudo apt -y autoremove
```


## Scanners

### nikto
```
sudo apt -y install nikto
```
### uniscan
```
sudo apt -y install libwww-perl liblog-any-adapter-log4perl-perl uniscan
sudo ln -vs /usr/share/uniscan/uniscan.conf /etc/uniscan.conf
```
Reports are stored in */usr/share/uniscan/*

