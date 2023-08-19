# RobotX
This repository for shared files was created to compete in the Virtual RobotX Competition

The files here will be the Dockerfile for the team's image and supporting files. 

The Dockerfile and supporting material were originally created from the minimal working example of a system provided by the host. The subdirectory TI_VRX_Docker will be replicated on every workstation and kept current with the master on this repository.

Until one of the team members thinks of a better way, we will just stick with the process supplied by the contest host.

export USERNAME=<username on Docker>

export IMAGE_NAME=<name of this image>

export TAG=<version of this image>

docker build --tag ${USERNAME}/${IMAGE_NAME}:${TAG} 



