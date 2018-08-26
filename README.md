Introduction
---
This image is running an Ether-1 (ETHO) Master node / Service node

**GitHub:** https://github.com/zibastian-mn/docker-masternode-ether1/  
**Docker:** https://hub.docker.com/r/zibastian/masternode-ether1/

---
Starting a node
---
```sh
docker run -d --restart=unless-stopped \
               -v etho-node:/opt/etho -p 30305:30305 \
               zibastian/masternode-ether1
```

---
Uninstall
---
```sh
docker rm -f <CONTAINER_NAME> && docker volume rm etho-node
```
---
Container logs
---
```bash
docker logs -f <CONTAINER_NAME> [--tail 20]
```

---
Donation
---
If this image helps you reduce time to deploy, I like beer :)

**EGEM:** 0x720752E61664a1B81B2ec9F7E709D0bCDB55502f  
**ETH:** 0x13B0E1c351e4a9Eae4980ae5469022808C8B3B6D  
**LTC:** MBiWJ3HB69nXtfxvdFmZE5iGm5AXWPRZuh  
**BTC:** 3NshfttcuYKNrU8CCwFqzuu8x95VtGQeu4  
