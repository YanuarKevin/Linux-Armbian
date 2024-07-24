# Linux-Armbian
Armbian OS 24.8.0 Bullseye with Linux 6.6.36-ophub

open with terminal pc: ssh hg680p@192.168.1.11
update ripositories: sudo apt update
list update ripo: apt list --upgradable
upgrade ripo: sudo apt upgrade
upgrade & configurate and delete old version ripo: sudo apt full-upgrade
sevice prome: sudo systemctl start service-name
              sudo systemctl stop service-name
              sudo systemctl status service-name
status check ngrok: sudo systemctl status ngrok
status check blynk server: ps aux | grep blynk
status chech zerotier: sudo systemctl status zerotier-one
ALL status active check: systemctl list-units --type=service --state=running
ALL status not active check: systemctl list-units --type=service
ALL status check: systemctl --type=service --all
