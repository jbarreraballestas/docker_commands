# Comandos docker

> correr el contenedor hello-world 
```
docker run hello-world
```

> listar los contenedores activos
```
docker ps
```

> listar todos los contenedores
```
docker ps -a
```

> mostrar el detalle completo de un contenedor por su id
```
docker inspect <containe ID> 
```

> mostrar el detalle completo de un contenedor por su nombre
```
docker inspect <name> 
```

> asignar el nombre personalizado “hola-mundo”
```
docker run –-name hola-mundo hello-world
```

> cambiar el nombre de hola-mundo a hola-github
```
docker rename hola-mundo hola-github
```

> borrar un contenedor
```
docker rm <ID o nombre>
```

> borrar todos lo contenedores que esten parados
```
docker container prune
```
