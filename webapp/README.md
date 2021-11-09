## API

## Docker build

```bash
docker build -t webapp:debug .
```

### Run API
```bash
docker run -p 80:80 -v ${PWD}/website:/var/www/html/ -e INSTANCE_STATUS=test -e API_URL=192.168.1.13 webapp:debug
python3 api.py
```
