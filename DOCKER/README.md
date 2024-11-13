## Eliminar `image` de docker

```bash
docker rmi <id image>
# with force
docker rmi <id image> -f
```

## Limpiar recursos de docker

- `docker system prune -f` para eliminar contenedores parados, redes sin uso, imágenes colgantes y cachés de construcción.
- `docker volume prune -f` para eliminar volúmenes en desuso.
- `docker image prune -f` para eliminar imágenes no utilizadas.


