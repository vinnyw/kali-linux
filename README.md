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
sudo ln -fvs /usr/share/uniscan/uniscan.conf /etc/uniscan.conf
sudo sed -i '/^url_encode/s/=.*$/=1/' /etc/uniscan.conf
sudo sed -i '/^autoupdate/s/=.*$/=0/' /etc/uniscan.conf
```
Reports and logs are stored in */usr/share/uniscan/*

