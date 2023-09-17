# Build Base Docker image
```
# make nvidia docker working
# follow this guide: https://github.com/NVIDIA/nvidia-docker

# build image
docker build -t tkdnn:latest -f Dockerfile.base .

#Run Docker
./docker_launch1.sh
