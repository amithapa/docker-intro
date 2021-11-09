## API

## Docker build

```bash
docker build -t api:debug .
```

### Run API
```bash
docker run -p 8989:8989 -v ${PWD}/src:/app -it api:debug /bin/bash
python3 api.py
```
