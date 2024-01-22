FROM debian
## enable non-free

RUN sed -i 's/bookworm main/bookworm main non-free non-free-firmware/g' /etc/apt/sources.list

# install cudnn
RUN apt-get update && apt-get install -y \
    nvidia-cudnn
