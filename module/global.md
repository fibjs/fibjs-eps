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
| sync            |                                         | sync(func)                     |

## property

| property | Node.js v7 |           fibjs            |
|----------|----------- |----------------------------|
|          | Buffer     | Buffer                     |
|          | __dirname  | readonly String __dirname  |
|          | __filename | readonly String __filename |
|          | exports    |                            |
|          | global     | readonly Object global     |
|          | module     |                            |
|          | process    | process                    |
|          | console    | console                    |
|          |            | Int64                      |
|          |            | readonly Array 	argv       |
