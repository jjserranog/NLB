#Prerequisitos tener un  docker / podman y el  docker-compose

#### 

sudo docker-compose up --build #compila y construye los 3 contendores.

#####

Se configuran 3 containers: 2 servidores web nginx que sirven 1 index.html  con un texto  y un nginx que balancea sobre ellos.


nginx con app1 que escucha en puerto 5001
nginx con app1 que escucha en puerto 5002
nginx lb que escucha en 8080 y balancea sobre los 2 anteriores 
