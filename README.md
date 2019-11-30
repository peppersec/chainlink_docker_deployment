1. To install docker:
```
docker-machine create --driver generic --generic-ip-address=IP geth-mainnet
```

2. Copy certs to remote instances:
run `env`
copy what is in. Example `DOCKER_CERT_PATH=/Users/$USER/.docker/machine/machines/$MACHINE`
`scp -r /Users/$USER/.docker/machine/machines/$MACHINE root@IP:/data/certs`