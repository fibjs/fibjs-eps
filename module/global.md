# global

module

## method

|       API       |               Node.js v7                |            fibjs               |
|-----------------|-----------------------------------------|--------------------------------|
| clearImmediate  | clearImmediate(immediateObject)         | clearImmediate(t)              |
| clearInterval   | clearInterval(intervalObject)           | clearInterval(t)               |
| clearTimeout    | clearTimeout(timeoutObject)             | clearTimeout(t)                |
| GC              |                                         | GC()                           |
| repl            |                                         | repl(cmds=[])                  |
| repl            |                                         | repl(Stream out, cmds=[])      |
| require         | require()                               | Value require(id)              |
| require.resolve | require.resolve()                       |                                |
| run             |                                         | run(fname, argv=[])            |
| setImmediate    | setImmediate(callback[, ...args])       | setImmediate(callback)         |
| setInterval     | setInterval(callback, delay[, ...args]) | setInterval(callback, timeout) |
| setTimeout      | setTimeout(callback, delay[, ...args])  | setTimeout(callback, timeout)  |

## property

| property  | Node.js v7 |           fibjs            |
|-----------|----------- |----------------------------|
|Buffer     | Buffer     | Buffer                     |
|__dirname  | __dirname  | readonly String __dirname  |
|__filename | __filename | readonly String __filename |
|exports    | exports    |                            |
|global     | global     | readonly Object global     |
|module     | module     |                            |
|process    | process    | process                    |
|console    | console    | console                    |
|Int64      |            | Int64                      |
|argv       |            | readonly Array 	argv      |
