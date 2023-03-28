# ieb_challenge

This is a repository for the ieb_challenge.

## Instalacion

para levantar los contenedores de docker

```bash
docker-compose up -d
```

parar los contenedores de docker

```bash
docker-compose down
```

para eliminar el folder de volume de docker ( a veces en algun rebuild hay que eliminarlo manualmente)

```bash
sudo rm -rf ieb_service_http/volume/
```

### Uso

para ver los logs de los contenedores

```bash
docker-compose logs -f <nombre del contenedor>
```

se puede levantar cada aplicacion localmente (instrucciones en cada repo).
la unica salvedad es que debe existir una db con las caracteristicas descriptas en el .env.example
