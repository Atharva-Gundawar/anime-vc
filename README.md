# comiCall

Install dependencies and prepare the build directory:

```sh
npm install
```


To broker connections, PeerJS connects to a PeerServer.
Note that no peer-to-peer data goes through the server; The server acts only as a connection broker.

PeerServer is open source and is written in node.js. You can easily run your own.

```sh
npm install peer
```

```sh
peerjs --port 3000
```