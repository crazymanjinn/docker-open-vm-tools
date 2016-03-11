# docker-open-vm-tools
open-vm-tools for docker container

needs to be run with --net=host and --privileged. e.g.,:
docker run -d --restart=always --net=host --privileged=true crazymanjinn/open-vm-tools
