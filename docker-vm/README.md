# docker-vm

Docker running on an Ubuntu VM on my desktop

Docker compose folders are in /opt/

# Used Ports 

- 9001 - portainer_agent
- 51820 - wg-easy
- 51821 - wg-easy

# To Do

- Add notifications from watchtower to ntfy


# Notes

wg-easy

- Router 192.168.1.1 set my Deco router 129.168.1.237 as the DMZ
- In the Deco app, go to more (bottom menu), Advanced, NAT Forwarding, Port Forwarding, and set wireguard udp 51820 to 192.168.68.202
- If wg-easy is moved to a different IP, this needs to be updated

