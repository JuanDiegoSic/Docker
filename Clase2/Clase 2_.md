# Clase 2:
Seguimos con la practica y nuestro primer entorno docker, utilizando una maquina virtual y MobaXterm para su manipulacion se jecutaron algunas lineas de codigo:


* Realizar una actualización:
    sudo apt-get update
    
* sudo apt-get install \
apt-transport-https \
ca-certificates \
curl \
gnupg-agent \
software-properties-common

* curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

* sudo add-apt-repository \
"deb [arch=amd64] https://download.docker.com/linux/ubuntu \
$(lsb_release -cs) \ stable"

* sudo apt-get update

* sudo apt-get install docker-ce docker-ce-cli containerd.io

validando con la ip del host local se valida su funcionamiento y fue posible trabajar con Docker




