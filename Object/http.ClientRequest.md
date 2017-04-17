
# http.ClientRequest

Object

- Node.js : http.ClientRequest
- fibjs : http.Request

## Class: http.ClientRequest

```js
```

### constructor

|    Node.js v7    |         fibjs      |
|------------------|--------------------|
|                  | new HttpRequest () |

### member

|        method     |                     Node.js v7               |                 fibjs                 |
|-------------------|----------------------------------------------|---------------------------------------|
|abort              | abort()                                      |                                       |
|end                | end([data][, encoding][, callback])          | end()                                 |
|flushHeaders       | flushHeaders()                               |                                       |
|setNoDelay         | setNoDelay([noDelay])                        |                                       |
|setSocketKeepAlive | setSocketKeepAlive([enable][, initialDelay]) |                                       |
|setTimeout         | setTimeout(timeout[, callback])              |                                       |
|write              | write(chunk[, encoding][, callback])         | write(Buffer data) async              |
|hasHeader          |                                              | Boolean hasHeader(String name)        |
|firstHeader        |                                              | Variant firstHeader(String name)      |
|allHeader          |                                              | List allHeader(String name)           |
|addHeader          |                                              | addHeader(Map map)                    |
|addHeader          |                                              | addHeader(String name, Variant value) |
|setHeader          |                                              | setHeader(Map map)                    |
|setHeader          |                                              | setHeader(String name, Variant value) |
|removeHeader       |                                              | removeHeader(String name)             |
|read               |                                              | Buffer read(Integer bytes=-1) async   |
|readAll            |                                              | Buffer readAll() async                |
|isEnded            |                                              | Boolean isEnded()                     |
|clear              |                                              | clear()                               |
|sendTo             |                                              | sendTo(Stream stm) async              |
|readFrom           |                                              | readFrom(Stream stm) async            |
|dispose            |                                              | dispose()                             |
|equals             |                                              | Boolean equals(object expected)       |
|toString           |                                              | String toString()                     |
|toJSON             |                                              | Value toJSON(String key="")           |
|valueOf            |                                              | Value valueOf()                       |

### Event

|  Event  |  Node.js v7 | fibjs |
|---------|-------------|-------|
|abort    | abort       |       |
|aborted  | aborted     |       |
|connect  | connect     |       |
|continue | continue    |       |
|response | response    |       |
|socket   | socket      |       |
|upgrade  | upgrade     |       |

## property

|   property     |   Node.js v7  |             fibjs               |
|----------------|---------------|---------------------------------|
|aborted         | aborted       |                                 |
|method          |               | String method                   |
|address         |               | String address                  |
|queryString     |               | String queryString              |
|cookies         |               | readonly HttpCollection cookies |
|form            |               | readonly HttpCollection form    |
|query           |               | readonly HttpCollection query   |
|protocol        |               | String protocol                 |
|headers         |               | readonly HttpCollection headers |
|keepAlive       |               | Boolean keepAlive               |
|upgrade         |               | Boolean upgrade                 |
|maxHeadersCount |               | Integer maxHeadersCount         |
|maxUploadSize   |               | Integer maxUploadSize           |
|1               |               | const TEXT = 1                  |
|2               |               | const BINARY = 2                |
|value           |               | String value                    |
|params          |               | List params                     |
|type            |               | Integer type                    |
|data            |               | readonly Value data             |
|body            |               | SeekableStream body             |
|length          |               | readonly Long length            |
|stream          |               | readonly Stream stream          |
|response        |               | readonly Message response       |
|lastError       |               | String lastError                |
