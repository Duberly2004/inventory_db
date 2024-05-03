## Database for project inventory


## MER
<image src="public/preview.jpeg" alt="Descripción de la imagen">

## Create database
```docker
docker run -d -p 27017:27017 --name inventory-mongo -e MONGO_INITDB_ROOT_USERNAME=root -e MONGO_INITDB_ROOT_PASSWORD=mipassword mongo 
```

```Docker
docker exec -it inventory-mongo mongosh -u root -p mipassword
``` 

```mongodb
show dbs
``` 
