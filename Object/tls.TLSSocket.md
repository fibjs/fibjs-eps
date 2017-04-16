
# tls.TLSSocket

Object

- Node.js: TLSSocket
- fibjs: SslSocket

## Class: tls.TLSSocket

```js

// const ssl = require('ssl');
const tls = require('tls');

// const s = new ssl.Socket();
const s = new ssl.TLSSocket();


```

### constructor

|             Node.js v7               |                fibjs               |
|--------------------------------------|------------------------------------|
| new tls.TLSSocket(socket[, options]) |                                    |
|                                      | SslSocket (Array certs=[])         |
|                                      | SslSocket (X509Cert crt, PKey key) |

### member

|        method      |             Node.js v7            |  fibjs |
|--------------------|-----------------------------------|--------|
|address             | address()                         |        |
|getCipher           | getCipher()                       |        |
|getEphemeralKeyInfo | getEphemeralKeyInfo()             |        |
|getPeerCertificate  | getPeerCertificate([ detailed ])  |        |
|getProtocol         | getProtocol()                     |        |
|getSession          | getSession()                      |        |
|getTLSTicket        | getTLSTicket()                    |        |
|renegotiate         | renegotiate(options, callback)    |        |
|setMaxSendFragment  | setMaxSendFragment(size)          |        |
|connect             |                                   | Integer connect(Stream s, String server_name="") async|
|accept              |                                   | SslSocket accept(Stream s) async|
|read                |                                   | Buffer read(Integer bytes=-1) async|
|write               |                                   | write(Buffer data) async|
|close               |                                   | close() async|
|copyTo              |                                   | Long copyTo(Stream stm, Long bytes=-1) async|
|dispose             |                                   | dispose()|
|equals              |                                   | Boolean equals(object expected)|
|toString            |                                   | String toString()|
|toJSON              |                                   | Value toJSON(String key="")|
|valueOf             |                                   | Value valueOf()|

### Event

|       Event     |    Node.js v7    |  fibjs |
|-----------------|------------------|--------|
|OCSPResponse     | OCSPResponse     |        |
|secureConnect    | secureConnect    |        |

## property

|      property     |     Node.js v7     |          fibjs             |
|-------------------|--------------------|----------------------------|
|authorized         | authorized         |                            |
|encrypted          | encrypted          |                            |
|localAddress       | localAddress       |                            |
|localPort          | localPort          |                            |
|remoteAddress      | remoteAddress      |                            |
|remoteFamily       | remoteFamily       |                            |
|remotePort         | remotePort         |                            |
|authorizationError | authorizationError |                            |
|verification       |                    | Integer verification       |
|ca                 |                    | readonly X509Cert ca       |
|peerCert           |                    | readonly X509Cert peerCert |
|stream             |                    | readonly Stream stream     |
