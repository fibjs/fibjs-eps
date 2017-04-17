# http

module

## method

|   method    |              Node.js v7         |                       fibjs                   |
|-------------|---------------------------------|-----------------------------------------------|
|createServer | createServer([requestListener]) |                                               |
|get          | get(options[, callback])        |                                               |
|request      | request(options[, callback])    |                                               |
|fileHandler  |                                 | fileHandler(root, mimes={})                   |
|request      |                                 | request(Stream conn, HttpRequest req) async   |
|request      |                                 | request(method, url, headers={})              |
|request      |                                 | request(method, url, Buffer body, headers={}) |
|get          |                                 | get(url, headers={})                          |
|post         |                                 | post(url, SeekableStream body, headers={})    |
|post         |                                 | post(url, Buffer body, headers={})            |
|post         |                                 | post(url, headers={})                         |
|del          |                                 | del(url, headers={})                          |
|put          |                                 | put(url, SeekableStream body, headers={})     |
|put          |                                 | put(url, Buffer body, headers={})             |
|put          |                                 | put(url, headers={})                          |
|patch        |                                 | patch(url, SeekableStream body, headers={})   |
|patch        |                                 | patch(url, Buffer body, headers={})           |
|patch        |                                 | patch(url, headers={})                        |

## property

|    property    |     Node.js v7  |        fibjs          |
|----------------|-----------------|-----------------------|
|METHODS         | METHODS         |                       |
|STATUS_CODES    | STATUS_CODES    |                       |
|globalAgent     | globalAgent     |                       |
|Agent           | Agent           |                       |
|ClientRequest   | ClientRequest   |                       |
|Server          | Server          |                       |
|ServerResponse  | ServerResponse  |                       |
|IncomingMessage | IncomingMessage |                       |
|cookies         |                 | readonly List cookies |
|timeout         |                 | Integer timeout       |
|enableCookie    |                 | Boolean enableCookie  |
|autoRedirect    |                 | Boolean autoRedirect  |
|userAgent       |                 | String userAgent      |
|Request         |                 | Request               |
|Response        |                 | Response              |
|Cookie          |                 | Cookie                |
|Server          |                 | Server                |
|Client          |                 | Client                |
|HttpsServer     |                 | HttpsServer           |
|Handler         |                 | Handler               |
