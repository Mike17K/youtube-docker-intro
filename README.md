# Docker Basic CLI

## Simple Build
```bash
docker build <dockerfile path>
```

## Build with Tag
```bash
docker build -t my-mysql-image <dockerfile path>
```

## Run Container
```bash
docker run -d -p 3306:3306 --name my-mysql-container my-mysql-image
```

## Look into the container
```bash
docker exec -it <containerid> /bin/bash
```