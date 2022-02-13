# OpenVpn

Server1
```
sudo su -
apt install openvpn
cd /etc/openvpn
openvpn --genkey --secret ta.key
openssl dhparam -out dh2048.pem 2048
nano server_ss.conf
 - (the next picture is the configuration for the server_ss(site to site))
nano server_ra.conf
 - (the next picture is the configuration for the server_ra)
```
