# Mongo GUI with AWS RDS support

A web ui for mongo by https://github.com/arunbandari/

Modified to support SSL. Supports AWS RDS certs so you can deploy it in AWS to access a DocumentDB if you need to. Use the `:rds` tag for that functionality.

```shell
docker run -p 4321:4321 -it alexanderczigler/mongo-gui
docker run -p 4321:4321 -it alexanderczigler/mongo-gui:rds # For AWS RDS.
```
