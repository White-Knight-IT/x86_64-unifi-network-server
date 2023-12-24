# x86_64-unifi-network-server
A docker image running MongoDB 4.4 + OpenJDK 17 + Unifi Network Server, all compatible with x86_64 Linux devices

Install docker + docker compose

git clone this repo

sudo docker-compose up -d

If you have a firewall such as UFW make sure you open at a minimum these local ingress ports on your host (the device running the docker container) https://help.ui.com/hc/en-us/articles/218506997-UniFi-Network-Required-Ports-Reference

That's it, access via https://host-ip-address:8443

Built and working on a Protectli FW4B (Intel Celeron J3160) with Unifi Network Server 8.0.24-24385-1
