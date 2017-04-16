
# tls.Server

Object

- Node.js: tls.Server
- fibjs: ssl.Server

## Class: tls.Server

```js

```

### constructor

|Node.js v7 |                                     fibjs                                  |
|-----------|----------------------------------------------------------------------------|
|           |SslServer(Array certs, Integer port, Value listener)                        |
|           |SslServer(Array certs, String addr, Integer port, Value listener)           |
|           |SslServer(X509Cert crt, PKey key, Integer port, Value listener)             |
|           |SslServer(X509Cert crt, PKey key, String addr, Integer port, Value listener)|

### member

|     method   |             Node.js v7               |                 fibjs           |
|--------------|--------------------------------------|---------------------------------|
|addContext    | addContext(hostname, context)        |                                 |
|address       | address()                            |                                 |
|close         | close([callback])                    |                                 |
|getTicketKeys | getTicketKeys()                      |                                 |
|listen        | listen(port[, hostname][, callback]) |                                 |
|setTicketKeys | setTicketKeys(keys)                  |                                 |
|run           |                                      | run() async                     |
|asyncRun      |                                      | asyncRun()                      |
|stop          |                                      | stop() async                    |
|dispose       |                                      | dispose()                       |
|Boolean       |                                      | Boolean equals(object expected) |
|String        |                                      | String toString()               |
|Value         |                                      | Value toJSON(String key="")     |
|Value         |                                      | Value valueOf()                 |

### Event

|       Event     |    Node.js v7    |  fibjs |
|-----------------|------------------|--------|
|newSession       | newSession       |        |
|OCSPRequest      | OCSPRequest      |        |
|resumeSession    | resumeSession    |        |
|secureConnection | secureConnection |        |
|tlsClientError   | tlsClientError   |        |

## property

|  property   |  Node.js v7 |         fibjs          |
|-------------|-------------|------------------------|
|connections  | connections |                        |
|verification |             | Integer verification   |
|ca           |             | readonly X509Cert ca   |
|socket       |             | readonly Socket socket |
|handler      |             | Handler handler        |
|stats        |             | readonly Stats stats   |
