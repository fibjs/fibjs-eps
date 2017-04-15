# ChildProcess

Object

- Node.js: ChildProcess
- fibjs: SubProcess

## Class: EventEmitter

### member

|  method   |      Node.js v7       |                         fibjs                        |
|-----------|-----------------------|------------------------------------------------------|
|disconnect | disconnect()          |                                                      |
|disconnect | disconnect()          |                                                      |
|kill       | kill([signal])        | kill(Integer signal)                                 |
|send       | send(message[, sendHandle[, options]][, callback]) |                         |
|wait       |                       | Integer wait() async                                 |
|findWindow |                       | Value findWindow(String name)                        |
|readText   |                       | String readText(Integer size) async                  |
|readLine   |                       | String readLine(Integer maxlen=-1) async             |
|readLines  |                       | Array readLines(Integer maxlines=-1)                 |
|readUntil  |                       | String readUntil(String mk, Integer maxlen=-1) async |
|writeText  |                       | writeText(String txt) async                          |
|writeLine  |                       | writeLine(String txt) async                          |
|read       |                       | Buffer read(Integer bytes=-1) async                  |
|write      |                       | write(Buffer data) async                             |
|close      |                       | close() async                                        |
|copyTo     |                       | Long copyTo(Stream stm, Long bytes=-1) async         |
|dispose    |                       | dispose()                                            |
|equals     |                       | Boolean equals(object expected)                      |
|toString   |                       | String toString()                                    |
|toJSON     |                       | Value toJSON(String key="")                          |
|valueOf    |                       | Value valueOf()                                      |

| property |  Node.js v7 |              fibjs              |
|----------|-------------|---------------------------------|
|          | channel     |                                 |
|          | connected   |                                 |
|          | pid         | readonly Integer pid            |
|          | stderr      |                                 |
|          | stdin       | readonly BufferedStream stdin   |
|          | stdio       |                                 |
|          | stdout      | readonly BufferedStream 	stdout |
|          |             | readonly Stream 	stream         |
|          |             | String 	charset                |
|          |             | String 	EOL                    |

### Event

| Event | Node.js v7 |  fibjs |
|-------|------------|--------|
|       | close      |        |
|       | disconnect |        |
|       | error      |        |
|       | exit       |        |
|       | message    |        |
