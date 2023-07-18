# Raspberry_wifi_control
Quick start and code example to pilote actuators with a raspberry zero w from wifi.


## Setup Raspbian:
getting started guide: <https://www.raspberrypi.com/documentation/computers/getting-started.html>
Raspberry OS imager download page: <https://www.raspberrypi.com/software/>

## Remote access from windows: 
Remote access: <https://www.raspberrypi.com/documentation/computers/remote-access.html>
* From Raspberry terminal, type command hostname -I to get IP.
* From Windows terminal, type commande ssh user@IP, then yes, then session password.

## SSH connection by key: 
* key gen: <https://www.digitalocean.com/community/tutorials/how-to-configure-ssh-key-based-authentication-on-a-linux-server>
* ssh-copy-id for windows: <https://chrisjhart.com/Windows-10-ssh-copy-id/>
* Send public key to server, command: type C:\Users\Username\.ssh\id_rsa.pub | ssh User@IP "cat >> .ssh/authorized_keys"
* Disable password connection: <https://www.pragmaticlinux.com/2021/05/configure-ssh-for-login-without-a-password/>
