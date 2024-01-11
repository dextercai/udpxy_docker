![Docker Image Size (tag)](https://img.shields.io/docker/image-size/dextercai/udpxy/latest)
![GitHub License](https://img.shields.io/github/license/dextercai/udpxy_docker)

# How To Use?

```bash
sudo docker stop udpxy
sudo docker rm udpxy
sudo docker run --name udpxy \
 --network host \
 --restart always \
 -d dextercai/udpxy:latest \
 -v -T -p 4022 -m ens19
```
