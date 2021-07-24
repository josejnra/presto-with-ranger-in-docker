# Presto with Apache Ranger in Docker
docker-compose for development purposes.

## How to run
Building and pulling images. This will take several minutes.
```bash
docker-compose build
```
Then, just run:
```bash
docker-compose up -d
```

- Presto running at [http://localhost:8080](http://localhost:8080).
- Apache Ranger running at [http://localhost:6080](http://localhost:6080).

## Apache Ranger
User is `admin` and password is `ranger1234`.
