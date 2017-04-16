# tls

module

- Node.js: tls
- fibjs: ssl

```js
const tls = require('tls');

```

## method

|        API         |                       Node.js v7                    | fibjs |
|--------------------|-----------------------------------------------------|-------|
|connect             | connect(options[, callback])                        |connect (String url, Integer timeout=0) async       |
|connect             | connect(path[, options][, callback])                |       |
|connect             | connect(port[, host][, options][, callback])        |       |
|createSecureContext | createSecureContext(options)                        |       |
|createServer        | createServer([options][, secureConnectionListener]) |       |
|getCiphers          | getCiphers()                                        |       |
|setClientCert||setClientCert (X509Cert crt, PKey key)|
|loadClientCertFile||loadClientCertFile (String crtFile, String keyFile, String password="")|

## property

|       property     |     Node.js v7     |         fibjs        |
|--------------------|--------------------|----------------------|
|DEFAULT_ECDH_CURVE  | DEFAULT_ECDH_CURVE |                      |
|Socket              |                    | Socket               |
|TLSSocket           | TLSSocket          |                      |
|Handler             |                    | Handler              |
|Server              | Server             | Server               |
|VERIFY_NONE         |                    | VERIFY_NONE          |
|VERIFY_OPTIONAL     |                    | VERIFY_OPTIONAL      |
|VERIFY_REQUIRED     |                    | VERIFY_REQUIRED      |
|BADCERT_EXPIRED     |                    | BADCERT_EXPIRED      |
|BADCERT_REVOKED     |                    | BADCERT_REVOKED      |
|BADCERT_CN_MISMATCH |                    | BADCERT_CN_MISMATCH  |
|BADCERT_NOT_TRUSTED |                    | BADCERT_NOT_TRUSTED  |
|ssl3                |                    | ssl3                 |
|tls1                |                    | tls1                 |
|tls1_1              |                    | tls1_1               |
|tls1_2              |                    | tls1_2               |
|ca                  |                    | readonly X509Cert ca |
|verification        |                    | Integer verification |
|min_version         |                    | Integer min_version  |
|max_version         |                    | Integer max_version  |
