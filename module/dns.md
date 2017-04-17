# dns

module

## method

|     API      |               Node.js v7                |     fibjs         |
|--------------|-----------------------------------------|-------------------|
|getServers    | getServers()                            |                   |
|lookup        | lookup(hostname[, options], callback)   |                   |
|lookupService | lookupService(address, port, callback)  |                   |
|resolve       | resolve(hostname[, rrtype], callback)   |                   |
|resolve4      | resolve4(hostname[, options], callback) |                   |
|resolve6      | resolve6(hostname[, options], callback) |                   |
|resolveCname  | resolveCname(hostname, callback)        |                   |
|resolveMx     | resolveMx(hostname, callback)           |                   |
|resolveNaptr  | resolveNaptr(hostname, callback)        |                   |
|resolveNs     | resolveNs(hostname, callback)           |                   |
|resolvePtr    | resolvePtr(hostname, callback)          |                   |
|resolveSoa    | resolveSoa(hostname, callback)          |                   |
|resolveSrv    | resolveSrv(hostname, callback)          |                   |
|resolveTxt    | resolveTxt(hostname, callback)          |                   |
|reverse       | reverse(ip, callback)                   |                   |
|setServers    | setServers(servers)                     |                   |

## property

|       property      |       Node.js v7     |   fibjs    |
|---------------------|----------------------|------------|
|NODATA               | NODATA               |            |
|FORMERR              | FORMERR              |            |
|SERVFAIL             | SERVFAIL             |            |
|NOTFOUND             | NOTFOUND             |            |
|NOTIMP               | NOTIMP               |            |
|REFUSED              | REFUSED              |            |
|BADQUERY             | BADQUERY             |            |
|BADNAME              | BADNAME              |            |
|BADFAMILY            | BADFAMILY            |            |
|BADRESP              | BADRESP              |            |
|CONNREFUSED          | CONNREFUSED          |            |
|TIMEOUT              | TIMEOUT              |            |
|EOF                  | EOF                  |            |
|FILE                 | FILE                 |            |
|NOMEM                | NOMEM                |            |
|DESTRUCTION          | DESTRUCTION          |            |
|BADSTR               | BADSTR               |            |
|BADFLAGS             | BADFLAGS             |            |
|NONAME               | NONAME               |            |
|BADHINTS             | BADHINTS             |            |
|NOTINITIALIZED       | NOTINITIALIZED       |            |
|LOADIPHLPAPI         | LOADIPHLPAPI         |            |
|ADDRGETNETWORKPARAMS | ADDRGETNETWORKPARAMS |            |
|CANCELLED            | CANCELLED            |            |
