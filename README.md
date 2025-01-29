First open two `terminals/consoles`. One for the proxy and one for the server.

For each terminal navigate/cd into ether the proxy or server folder.

To start the proxy and server run the start script in each terminal. \
For example on mac: `sh start-mac-linux.sh`.

You can now connect with `localhost:25565`

I recommend changing the forwarding secret located in `proxy/forwarding.secret` \
 and `server/config/paper-global.proxy.vlocity.secret`

# Info

```yaml
proxy: 0.0.0.0:25565
server: 0.0.0.0:25566
```