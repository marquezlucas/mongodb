## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://root:tuki1511@localhost:27018/?tls=false"
mongosh "mongodb+srv://lucasadmin:Azcuenaga1908-@mongodb101.626fmpq.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("tuki_store")

db.products.find()

```