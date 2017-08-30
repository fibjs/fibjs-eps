# StringDecoder

Object

## Class: StringDecoder

```js
const StringDecoder = require('string_decoder').StringDecoder;
const decoder = new StringDecoder('utf8');

const cent = Buffer.from([0xC2, 0xA2]);
console.log(decoder.write(cent));

const euro = Buffer.from([0xE2, 0x82, 0xAC]);
console.log(decoder.write(euro));
```

### constructor

|           Node.js v7          |      fibjs      |
|-------------------------------|-----------------|
| new StringDecoder([encoding]) | StringDecoder(String encoding = "utf8") |

### member

| method |   Node.js v7  |   fibjs   |
|--------|---------------|-----------|
|end     | end([buffer]) | String end([Buffer buf]) |
|write   | write(buffer) | String write(Buffer buf) |
