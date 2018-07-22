# chat-simo
1 - installl node.js 
www.nodejs.com
2- npm init
###socket.io
## Installation

```bash
npm install socket.io --save
```

## How to use

The following example attaches socket.io to a plain Node.JS
HTTP server listening on port `3000`.

```js
var server = require('http').createServer();
var io = require('socket.io')(server);
io.on('connection', function(client){
  client.on('event', function(data){});
  client.on('disconnect', function(){});
});
server.listen(3000);
```

node index.js in cmd
go to http://localhost:1997
