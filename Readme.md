
## Testing the API with Postman



#### run by writing:
```bash
node index.js
```

Server requires a functioning local PostgreSQL driver with this database:
``` base
user:  "postgres"
host:  "localhost",
database:  "api",
password:  "bata123"
```
- Node-postgres was used to create a pool of connections between express server and local database
- Supports `GET`, `POST`, `PUT`, and `DELETE`  requests
- Video below shows, that server returns data in JSON format, as required in coding assessment

https://user-images.githubusercontent.com/46716452/188293113-f4029655-94b9-4f34-8daa-4dd31ad11419.mp4

