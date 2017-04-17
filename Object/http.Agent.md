
# http.Agent

Object

## Class: http.Agent

```js
const http = require('http');
const keepAliveAgent = new http.Agent({ keepAlive: true });
options.agent = keepAliveAgent;
http.request(options, onResponseCallback);
```

### constructor

|     Node.js v7       |   fibjs       |
|----------------------|---------------|
| new Agent([options]) |               |

### member

|        method      |                 Node.js v7            |  fibjs |
|--------------------|---------------------------------------|--------|
|createConnection    | createConnection(options[, callback]) |        |
|destroy             | destroy()                             |        |
|getName             | getName(options)                      |        |

## property

|      property     |     Node.js v7     |          fibjs             |
|-------------------|--------------------|----------------------------|
|freeSockets        | freeSockets        |                            |
|maxFreeSockets     | maxFreeSockets     |                            |
|maxSockets         | maxSockets         |                            |
|requests           | requests           |                            |
|sockets            | sockets            |                            |
