# docker-assignment
## To setting mysql, please follow this step
```
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '123';
ALTER USER 'users_service' IDENTIFIED WITH mysql_native_password BY '123';
flush privileges;
```

## To test containers, run this on bash

$ curl -L http://localhost/?username=alice | json_pp
