# JSON Server using ngrok

### Install module using `npm install` and you need to run two commands in two different terminal

```
npm run db
npm run tunnel
```

At the tunnel terminal: forwarding url is your api url
## Endpoints
Please check out the `db.json` file where each index is an endpoint of this server. You can add many endpoints if you want.

### Changing `http` port
Default port is `3000`. If you want to change the http port then you can change at `script` section at `package.json` file. like:
```
"db": "json-server -w db.json -p 3006",
"tunnel": "ngrok http 3006"
```
