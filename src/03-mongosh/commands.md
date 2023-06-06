# Connect to container
```sh
docker-compose exec mongodb bash
```
# Connect with mongosh

```sh
mongosh "mongodb://TryDante:H0BgPlz3FbBsMKEm@localhost:27017/?tls=false&authMechanism=DEFAULT"
mongosh "mongodb+srv://TryDante:H0BgPlz3FbBsMKEm@dantedb101.jbj9r8w.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("sample_mflix")
db.movies.find()
```
