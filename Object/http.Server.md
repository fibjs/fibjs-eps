
# http.Server

Object

## Class: http.Server

```js
```

### constructor

|     Node.js v7   |                          fibjs                    |
|------------------|---------------------------------------------------|
|                  | HttpServer(Integer port, Value hdlr)              |
|                  | HttpServer(String addr, Integer port, Value hdlr) |

### member

|  method   |                    Node.js v7                     |          fibjs          |
|-----------|---------------------------------------------------|-------------------------|
|close      | close([callback])                                 |                         |
|listen     | listen(handle[, callback])                        |                         |
|listen     | listen(path[, callback])                          |                         |
|listen     | listen([port][, hostname][, backlog][, callback]) |                         |
|setTimeout | setTimeout([msecs][, callback])                   |                         |
|onerror    |                                                   | onerror(Object hdlrs)   |
|run        |                                                   | run() async             |
|asyncRun   |                                                   | asyncRun()              |
|stop       |                                                   | stop() async            |
|dispose    |                                                   | dispose()               |
|equals     |                                                   | equals(object expected) |
|toString   |                                                   | toString()              |
|toJSON     |                                                   | toJSON(String key="")   |
|valueOf    |                                                   | valueOf()               |

### Event

|       Event     |     Node.js v7   |   fibjs |
|-----------------|------------------|---------|
|checkContinue    | checkContinue    |         |
|checkExpectation | checkExpectation |         |
|clientError      | clientError      |         |
|close            | close            |         |
|connect          | connect          |         |
|connection       | connection       |         |
|request          | request          |         |
|upgrade          | upgrade          |         |

## property

|   property     |     Node.js v7     |       fibjs     |
|----------------|--------------------|-----------------|
|timeout         | timeout            |                 |
|listening       | listening          |                 |
|maxHeadersCount | maxHeadersCount    | maxHeadersCount |
|crossDomain     |                    | crossDomain     |
|forceGZIP       |                    | forceGZIP       |
|maxUploadSize   |                    | maxUploadSize   |
|Stats           |                    | Stats httpStats |
|Socket          |                    | Socket socket   |
|handler         |                    | handler         |
|Stats           |                    | Stats stats     |
