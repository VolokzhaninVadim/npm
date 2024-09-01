# Nginx Proxy Manager
![npm.svg](./img/npm.svg)

## First launch
```bash
Email: admin@example.com
Password: changeme
```
Create network:
```bash
docker network create -d bridge your_network
```

Add service (docker container) in network:
```
docker network connect your_network your_service
```
