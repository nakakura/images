# It is forked from here.
# https://github.com/osrf/docker_images/blob/0b33e61b5bbed5b93b9fba2d5bae5db604ff9b58/ros/melodic/ubuntu/bionic/desktop-full/Dockerfile

FROM osrf/ros:melodic-desktop-bionic

RUN apt-get update && apt-get install -y --no-install-recommends \
    ros-melodic-desktop-full=1.4.1-0* \
    && apt-get update \
    && apt-get install -y python python-pip python-dev \
    && rm -rf /var/lib/apt/lists/* 
