# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:ubuntu-router_0.1_amd64.rock docker-daemon:ubuntu-router:0.1
docker run ubuntu-router:0.1
```
