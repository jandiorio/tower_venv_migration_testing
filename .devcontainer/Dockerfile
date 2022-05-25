FROM ubuntu:22.10

WORKDIR /code
COPY . .
RUN apt update && apt install -y git gcc python3 python3-pip podman

RUN pip install -r requirements.txt

# RUN mount --make-shared /host_mnt/
