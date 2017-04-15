# Event

Object

## Class: EventEmitter

```js

// const EventEmitter = require('events').EventEmitter;
const EventEmitter = require('events');

class MyEmitter extends EventEmitter {}

const myEmitter = new MyEmitter();
```

### static

|     method    |            Node.js v7             | fibjs |
|---------------|-----------------------------------|-------|
| listenerCount | listenerCount(emitter, eventName) |       |

### member

|       method        |                   Node.js v7             |               fibjs               |
|---------------------|------------------------------------------|-----------------------------------|
| addListener         | addListener(eventName, listener)         | Object addListener(ev, func)      |
| addListener         |                                          | Object addListener(map={})        |
| emit                | emit(eventName[, ...args])               | Boolean emit(ev,...)              |
| eventNames          | eventNames()                             |                                   |
| getMaxListeners     | getMaxListeners()                        |                                   |
| listenerCount       | listenerCount(eventName)                 |                                   |
| listeners           | listeners(eventName)                     |                                   |
| on                  | on(eventName, listener)                  | Object on( ev, func)              |
| on                  |                                          | Object on(map={})                 |
| once                | once(eventName, listener)                | Object once(ev, func)             |
| once                |                                          | Object once(Object map)           |
| prependListener     | prependListener(eventName, listener)     |                                   |
| prependOnceListener | prependOnceListener(eventName, listener) |                                   |
| removeAllListeners  | removeAllListeners([eventName])          | Object removeListener(ev, func)   |
| removeAllListeners  |                                          | Object removeListener(ev)         |
| removeAllListeners  |                                          | Object removeListener(map={})     |
| removeAllListeners  |                                          | Object removeAllListeners(evs=[]) |
| removeListener      | removeListener(eventName, listener)      |                                   |
| setMaxListeners     | setMaxListeners(n)                       | setMaxListeners(Integer n)        |
| off                 |                                          | Object off(ev, func)              |
| off                 |                                          | Object off(ev)                    |
| off                 |                                          | Object off(map={})                |
| listeners           |                                          | Array listeners(ev)               |

| property |      Node.js v7     | fibjs |
|----------|---------------------|-------|
|          | defaultMaxListeners |       |

### Event

| Event |   Node.js v7   | fibjs |
|-------|----------------|-------|
|       | newListener    |       |
|       | removeListener |       |
