
# http.IncomingMessage

Object

## Class: http.IncomingMessage

An IncomingMessage object is created by http.Server or http.ClientRequest and passed as the first argument to the 'request' and 'response' event respectively. It may be used to access response status, headers and data.

```js
```

### member

|  method   |     Node.js v7              |  fibjs |
|-----------|-----------------------------|--------|
|destroy    | destroy([error])            |        |
|setTimeout | setTimeout(msecs, callback) |        |

### Event

|  Event  |  Node.js v7 | fibjs |
|---------|-------------|-------|
|aborted  | aborted     |       |
|close    | close       |       |

## property

|   property   |  Node.js v7   |  fibjs   |
|--------------|---------------|----------|
|headers       | headers       |          |
|httpVersion   | httpVersion   |          |
|method        | method        |          |
|rawHeaders    | rawHeaders    |          |
|rawTrailers   | rawTrailers   |          |
|socket        | socket        |          |
|statusCode    | statusCode    |          |
|statusMessage | statusMessage |          |
|trailers      | trailers      |          |
|url           | url           |          |
