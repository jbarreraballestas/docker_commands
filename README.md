# Comandos docker

> correr el contenedor hello-world 
```
docker run hello-world
```

> muestra los contenedores activos
```
docker ps
```

> muestra todos los contenedores
```
docker ps -a
```

> muestra el detalle completo de un contenedor
```
docker inspect <containe ID> 
```

> igual que el anterior pero invocado con el nombre
```
docker inspect <name> 
```

> le asigno un nombre personalizado “hola-mundo”
```
docker run –-name hola-mundo hello-world
```

> cambio el nombre de hola-mundo a hola-github
```
docker rename hola-mundo hola-github
```

> borro un contenedor
```
docker rm <ID o nombre>
```

> borro todos lo contenedores que esten parados
```
docker container prune
```
