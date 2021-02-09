# tallerIaC

## Comandos utiles

Ejecutar playbook ansible con prompt para pass
```
ansible-playbook playbook.yml --ask-become-pass
```

Buildear imagen docker
```
docker build -t <image name> .
```

Ejecutar contenedor en modo detached con port forwarding
```
docker run -dp 8000:8080 <container name>
```

Conectarse a un contenedor por ssh usando id
```
docker exec -it <container id> /bin/bash 
```