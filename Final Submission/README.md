# QUIC-360° Video stream

Taken from [@najaco](https://github.com/najaco/quic-v-stream)


## How to run


### Run server
```sh
python -m src.server -c <certificate> -k <private_key> --host <ip_addr> --port <port no.>
```

### Run client
```sh
python -m src.client --host <ip_addr> --port <port_no> --request <file>
```
