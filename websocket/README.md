# websocket

Simple echo websocket server.

## Usage

### server

```bash
cd examples/websocket
cargo run --bin server
# Started http server: 127.0.0.1:8080
```

### web client

- [http://localhost:8080/index.html](http://localhost:8080/index.html)

### rust client

```bash
cd examples/websocket
cargo run --bin client
```

### python client

- ``pip install aiohttp``
- ``python websocket-client.py``

if ubuntu :

- ``pip3 install aiohttp``
- ``python3 websocket-client.py``
