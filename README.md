# QUIC-360° Video stream
## How to run

### Run server
```sh
python3 -m src.server -c ssl_cert.pem -k ssl_key.pem --host 127.0.0.1 --port 8000
```

### Run client
```sh
python -m src.client
```
