# Comandos docker

> correr el contenedor hello-world 
```
docker run hello-world
```
> ver documentación
```
docker run -h
```

> mostrar los contenedores
> 
> -a, --all             Mostrar todos los contenedores (por defecto solo muestra los que están corriendo)
> 
> -f, --filter filter   Filter output based on conditions provided
> 
> --format string   Pretty-print containers using a Go template
>     
> -n, --last int        Muestra los n últimos contenedores creados (todos los estados) (por defecto -1)
> 
> -l, --latest          Muestra el último contenedor creado (todos los estados)
> 
> --no-trunc        Don't truncate output
>     
> -q, --quiet           Muestro solo los IDs de los contenedores
> 
> -s, --size            Mostrar peso total de los archivos
```
docker ps -a
```

> mostrar el detalle completo de un contenedor por su id
```
docker inspect <container ID> 
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

> corre un contenedor ubuntu pero lo deja apagado
```
docker run ubuntu
```

> corre un contenedor ubuntu y entra al shell de ubuntu
>
> -i: interactivo
> 
> -t: abre la consola
```
docker run -it ubuntu
```
