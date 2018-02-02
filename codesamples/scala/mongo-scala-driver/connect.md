# Connect 

```
val mongoClient: MongoClient = MongoClient()
val database: MongoDatabase = mongoClient.getDatabase("mydb")
val collection: MongoCollection[Document] = database.getCollection("test")
```
