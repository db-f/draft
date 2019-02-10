FROM ros:melodic-ros-core

RUN apt-get update \
  && apt-get -y install python-pip \
  && rm -rf /var/lib/apt/lists/* \
  && pip install -U catkin_tools

COPY ./ /src
