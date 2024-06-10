# Run manualy
```bash
python -m uvicorn main:app --reload
```

## Build with docker
```bash
docker build -t my-fast-api-image .
```
## Run with docker
```bash
docker run -p "8000:8000" --name my-fast-api-container my-fast-api-image
```

## Info
Documentation on: [here](http://localhost:8000/docs)