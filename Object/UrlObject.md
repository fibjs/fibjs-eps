# UrlObject

Object

## Class: UrlObject

```js
```

### constructor

|     Node.js v7       |   fibjs       |
|----------------------|---------------|
|                      | new UrlObject(Object args) |

### member

|   method |  Node.js v7   |                        fibjs                      |
|----------|---------------|---------------------------------------------------|
|parse     |               | parse(String url, Boolean parseQueryString=false) |
|format    |               | format(Object args)                               |
|resolve   |               | UrlObject resolve(String url)                     |
|normalize |               | normalize()                                       |
|dispose   |               | dispose()                                         |
|equals    |               | Boolean equals(object expected)                   |
|toString  |               | String toString()                                 |
|toJSON    |               | Value toJSON(String key="")                       |
|valueOf   |               | Value valueOf()                                   |

## property

| property | Node.js v7 |       fibjs     |
|----------|------------|-----------------|
|href      | href       | String href     |
|protocol  | protocol   | String protocol |
|slashes   | slashes    | Boolean slashes |
|auth      | auth       | String auth     |
|username  |            | String username |
|password  |            | String password |
|host      | host       | String host     |
|hostname  | hostname   | String hostname |
|port      | port       | String port     |
|path      | path       | String path     |
|pathname  | pathname   | String pathname |
|search    | search     | String search   |
|query     | query      | Value query     |
|hash      | hash       | String hash     |
