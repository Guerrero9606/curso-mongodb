## Connect to container

```sh
docker-compose exec mongodb bash
```

## Connect to mongosh

```sh
mongosh "mongodb://root:root123@192.168.0.107:27017/?authMechanism=DEFAULT"
```

```sh
shows dbs
shows collections
```

```sh
use ("platzi_store")
db.products.find()
```
