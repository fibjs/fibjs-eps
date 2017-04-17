
# http.ServerResponse

Object

- Node.js : http.ServerResponse
- fibjs : http.Response

## Class: http.ServerResponse

```js
```

### constructor

|    Node.js v7    |         fibjs      |
|------------------|--------------------|
|                  | new HttpResponse() |

### member

|    method     |                    Node.js v7                     |                   fibjs               |
|---------------|---------------------------------------------------|---------------------------------------|
|addTrailers    | addTrailers(headers)                              |                                       |
|end            | end([data][, encoding][, callback])               | end()                                 |
|getHeader      | getHeader(name)                                   |                                       |
|getHeaderNames | getHeaderNames()                                  |                                       |
|getHeaders     | getHeaders()                                      |                                       |
|hasHeader      | hasHeader(name)                                   | Boolean hasHeader(String name)        |
|removeHeader   | removeHeader(name)                                | removeHeader(String name)             |
|setHeader      | setHeader(name, value)                            | setHeader(String name, Variant value) |
|setHeader      |                                                   | setHeader(Map map)                    |
|setTimeout     | setTimeout(msecs[, callback])                     |                                       |
|write          | write(chunk[, encoding][, callback])              | write(Buffer data) async              |
|writeContinue  | writeContinue()                                   |                                       |
|writeHead      | writeHead(statusCode[, statusMessage][, headers]) |                                       |
|addCookie      |                                                   | addCookie(HttpCookie cookie)          |
|redirect       |                                                   | redirect(String url)                  |
|sendHeader     |                                                   | sendHeader(Stream stm) async          |
|firstHeader    |                                                   | Variant firstHeader(String name)      |
|allHeader      |                                                   | List allHeader(String name)           |
|addHeader      |                                                   | addHeader(Map map)                    |
|addHeader      |                                                   | addHeader(String name, Variant value) |
|read           |                                                   | Buffer read(Integer bytes=-1) async   |
|readAll        |                                                   | Buffer readAll() async                |
|isEnded        |                                                   | Boolean isEnded()                     |
|clear          |                                                   | clear()                               |
|sendTo         |                                                   | sendTo(Stream stm) async              |
|readFrom       |                                                   | readFrom(Stream stm) async            |
|dispose        |                                                   | dispose()                             |
|equals         |                                                   | Boolean equals(object expected)       |
|toString       |                                                   | String toString()                     |
|toJSON         |                                                   | Value toJSON(String key="")           |
|valueOf        |                                                   | Value valueOf()                       |

### Event

|       Event     |     Node.js v7   |   fibjs |
|-----------------|------------------|---------|
|close            | close            |         |
|finish           | finish           |         |

## property

|   property     |  Node.js v7    |               fibjs             |
|----------------|----------------|---------------------------------|
|statusMessage   | statusMessage  |                                 |
|statusCode      | statusCode     |                                 |
|sendDate        | sendDate       |                                 |
|headersSent     | headersSent    |                                 |
|finished        | finished       |                                 |
|status          |                | Integer status                  |
|cookies         |                | readonly List cookies           |
|protocol        |                | String protocol                 |
|headers         |                | readonly HttpCollection headers |
|keepAlive       |                | Boolean keepAlive               |
|upgrade         |                | Boolean upgrade                 |
|maxHeadersCount |                | Integer maxHeadersCount         |
|maxUploadSize   |                | Integer maxUploadSize           |
|TEXT            |                | const TEXT = 1                  |
|BINARY          |                | const BINARY = 2                |
|value           |                | String value                    |
|params          |                | List params                     |
|type            |                | Integer type                    |
|data            |                | readonly Value data             |
|body            |                | SeekableStream body             |
|length          |                | readonly Long length            |
|stream          |                | readonly Stream stream          |
|response        |                | readonly Message response       |
|lastError       |                | String lastError                |
