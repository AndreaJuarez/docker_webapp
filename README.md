# docker_webapp
Versión 2.0 del proyecto "Introducción a Docker" para la materia Desarrollo web profesional. 

# descargar imagen
docker pull ubuntu:21.04

# crear contenedor
docker run -it -p 8080:8080 -v /workspace/docker_webapp/volume:/volume --name webpy -h webpy ubuntu:20.04

# ya en el contenedor 
apt update
apt install -y python3
apt install -y python3-pip
pip3 install web.py