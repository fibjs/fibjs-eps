# Buffer

Object

## Class: Buffer

```js
// Creates a zero-filled Buffer of length 10.
const buf1 = Buffer.alloc(10);

// Creates a Buffer of length 10, filled with 0x1.
const buf2 = Buffer.alloc(10, 1);

// Creates an uninitialized buffer of length 10.
// This is faster than calling Buffer.alloc() but the returned
// Buffer instance might contain old data that needs to be
// overwritten using either fill() or write().
const buf3 = Buffer.allocUnsafe(10);

// Creates a Buffer containing [0x1, 0x2, 0x3].
const buf4 = Buffer.from([1, 2, 3]);

// Creates a Buffer containing UTF-8 bytes [0x74, 0xc3, 0xa9, 0x73, 0x74].
const buf5 = Buffer.from('tést');

// Creates a Buffer containing Latin-1 bytes [0x74, 0xe9, 0x73, 0x74].
const buf6 = Buffer.from('tést', 'latin-1');
```

### constructor

|                     Node.js v7                  |                       fibjs                  |
|-------------------------------------------------|----------------------------------------------|
|new Buffer(array)                                | new Buffer (Array datas)                     |
|new Buffer(arrayBuffer[, byteOffset [, length]]) | new Buffer (ArrayBuffer datas)               |
|new Buffer(buffer)                               | new Buffer (Buffer buffer)                   |
|new Buffer(size)                                 | new Buffer (Integer size=0)                  |
|new Buffer(string[, encoding])                   | new Buffer (String str, String codec="utf8") |
|                                                 | new Buffer (TypedArray datas)                |

### static

|       method    |            Node.js v7           |               fibjs            |
|-----------------|---------------------------------|--------------------------------|
| alloc           | alloc(size[, fill[, encoding]]) | Buffer alloc(Integer size, Integer fill = 0, String codec = "utf8") |
| alloc           |                                 | Buffer alloc(Integer size, String fill = "", String codec = "utf8") |
| alloc           |                                 | Buffer alloc(Integer size, Buffer fill, String codec = "utf8") |
| allocUnsafe     | allocUnsafe(size)               | Buffer allocUnsafe(Integer size)|
| allocUnsafeSlow | allocUnsafeSlow(size)           | Buffer allocUnsafeSlow(Integer size)|
| byteLength      | byteLength(string[, encoding])  | Integer byteLength([String/ArrayBuffer/ArrayBufferView/Buffer] str, String codec = "utf8")|
| compare         | compare(buf1, buf2)             |                                |
| concat          | concat(list[, totalLength])     | concat (buflist, cutLength=-1) |
| from            | from(object[, offsetOrEncoding[, length]])          |                                |
| from            | from(array)                     |                                |
| from            | from(arrayBuffer[, byteOffset[, length]]) ||
| from            | from(buffer)                    |Buffer from(Buffer buffer, Integer byteOffset = 0, Integer length = -1)|
| from            | from(string[, encoding])        |Buffer from(String str, String codec = "utf8")|
| from            |                                 |Buffer from(String str, Integer byteOffset = 0, Integer length = -1)|
| isBuffer        | isBuffer(obj)                   | isBuffer (Value v)             |
| isEncoding      | isEncoding(encoding)            | Boolean isEncoding(String codec)|

|   property  |  Node.js v7  | fibjs |
|-------------|----------------|-------|
|             |  poolSize      |       |

### member

|       method        |    Node.js v7             |               fibjs               |
|---------|------------------------------------------|---------------------------------|
|append        |                                              | append(Array datas) |
|append        |                                              | append(TypedArray datas) |
|append        |                                              | append(ArrayBuffer datas) |
|append        |                                              | append(Buffer data) |
|append        |                                              | append(String str, String codec="utf8") |
|base64        |                                              | base64()          |
|compare       | compare(target[, targetStart[, targetEnd[, sourceStart[, sourceEnd]]]])|   |
|compare       |                                              | compare(Buffer buf)              |
|copy          | copy(target[, targetStart[, sourceStart[, sourceEnd]]])|copy(targetBuffer, targetStart=0, sourceStart=0, sourceEnd=-1)|
|entries       | entries()                                    | Iterator entries() |
|equals        | equals(otherBuffer)                          | equals (object expected)         |
|fill          | fill(value[, offset[, end]][, encoding])     |                                  |
|fill          |                                              | fill(v=0, offset=0, end=-1)      |
|fill          |                                              | fill(Buffer v, offset=0, end=-1) |
|fill          |                                              | fill(String v, offset=0, end=-1) |
|hex           |                                              | hex()                            |
|includes      | includes(value[, byteOffset][, encoding])    |                                  |
|indexOf       | indexOf(value[, byteOffset][, encoding])     |                                  |
|indexOf       |                                              | indexOf(Integer v, offset=0)     |
|indexOf       |                                              | indexOf(Buffer v, offset=0)      |
|indexOf       |                                              | indexOf(String v, offset=0)      |
|keys          | keys()                                       | Iterator keys();                   |
|lastIndexOf   | lastIndexOf(value[, byteOffset][, encoding]) |   |
|readDoubleBE  | readDoubleBE(offset[, noAssert])             | readDoubleBE(offset=0, noAssert=false)  |
|readDoubleLE  | readDoubleLE(offset[, noAssert])             | readDoubleLE(offset=0, noAssert=false)  |
|readFloatBE   | readFloatBE(offset[, noAssert])              | readFloatBE(offset=0, noAssert=false)  |
|readFloatLE   | readFloatLE(offset[, noAssert])              | readFloatLE(offset=0, noAssert=false)  |
|readInt8      | readInt8(offset[, noAssert])                 | readInt8(offset=0, noAssert=false)    |
|readInt16BE   | readInt16BE(offset[, noAssert])              | readInt16BE(offset=0, noAssert=false)  |
|readInt16LE   | readInt16LE(offset[, noAssert])              | readInt16LE(offset=0, noAssert=false)  |
|readInt32BE   | readInt32BE(offset[, noAssert])              | readInt32BE(offset=0, noAssert=false)  |
|readInt32LE   | readInt32LE(offset[, noAssert])              | readInt32LE(offset=0, noAssert=false)  |
|readIntBE     | readIntBE(offset, byteLength[, noAssert])    | readIntBE(offset=0, noAssert=false)  |
|readIntLE     | readIntLE(offset, byteLength[, noAssert])    | readIntLE(offset=0, noAssert=false) |
|readUInt8     | readUInt8(offset[, noAssert])                | readUInt8(offset=0, noAssert=false) |
|readUInt16BE  | readUInt16BE(offset[, noAssert])             | readUInt16BE(offset=0, noAssert=false) |
|readUInt16LE  | readUInt16LE(offset[, noAssert])             | readUInt16LE(offset=0, noAssert=false) |
|readUInt32BE  | readUInt32BE(offset[, noAssert])             | readUInt32BE(offset=0, noAssert=false) |
|readUInt32LE  | readUInt32LE(offset[, noAssert])             | readUInt32LE(offset=0, noAssert=false) |
|readInt64LE   |                                              | readInt64LE(offset=0, noAssert=false) |
|readInt64BE||readInt64BE(offset=0, noAssert=false)|
|readUIntBE    | readUIntBE(offset, byteLength[, noAssert])   | readUIntBE(offset=0, noAssert=false)   |
|readUIntLE    | readUIntLE(offset, byteLength[, noAssert])   | readUIntLE(offset=0, noAssert=false)   |
|resize||resize (Integer sz)|
|slice         | slice([start[, end]])                        |slice(start=0),slice(start, end)|
|swap16        | swap16()                                     |   |
|swap32        | swap32()                                     |   |
|swap64        | swap64()                                     |   |
|to            |                                              | to(codec, offset=0, end=-1)   |
|toArray       |                                              | toArray()                     |
|toJSON        | toJSON()                                     | toJSON (String key="")  |
|toString      | toString([encoding[, start[, end]]])         |toString (codec, offset=0, end=-1) |
|values        | values()                                     | Iterator values()        |
|write         | write(string[, offset[, length]][, encoding])|write(str, offset=0, length=-1, codec="utf8")|
|write||write(str, offset=0, codec="utf8")|
|write||write(str, codec="utf8")|
|writeDoubleBE | writeDoubleBE(value, offset[, noAssert])     |writeDoubleBE(value, offset, noAssert=false)|
|writeDoubleLE | writeDoubleLE(value, offset[, noAssert])     |writeDoubleLE(value, offset, noAssert=false)|
|writeFloatBE  | writeFloatBE(value, offset[, noAssert])      |writeFloatBE(value, offset, noAssert=false)|
|writeFloatLE  | writeFloatLE(value, offset[, noAssert])      |writeFloatLE(value, offset, noAssert=false)|
|writeInt8     | writeInt8(value, offset[, noAssert])         |writeInt8(value, offset=0, noAssert=false) |
|writeInt16BE  | writeInt16BE(value, offset[, noAssert])      |writeInt16BE(value, offset=0, noAssert=false)|
|writeInt16LE  | writeInt16LE(value, offset[, noAssert])      |writeInt16LE(value, offset=0, noAssert=false)|
|writeInt32BE  | writeInt32BE(value, offset[, noAssert])      |writeInt32BE(value, offset=0, noAssert=false)|
|writeInt32LE  | writeInt32LE(value, offset[, noAssert])      |writeInt32LE(value, offset=0, noAssert=false)|
|writeInt64LE||writeInt64LE(value, offset=0, noAssert=false)|
|writeInt64BE||writeInt64BE(value, offset=0, noAssert=false)|
|writeIntBE    | writeIntBE(value, offset, byteLength[, noAssert])|writeIntBE(value, offset=0, noAssert=false)|
|writeIntLE    | writeIntLE(value, offset, byteLength[, noAssert])|writeIntLE(value, offset=0, noAssert=false)|
|writeUInt8    | writeUInt8(value, offset[, noAssert])        | writeUInt8(value, offset=0, noAssert=false)|
|writeUInt16BE | writeUInt16BE(value, offset[, noAssert])    |writeUInt16BE(value, offset=0, noAssert=false)|
|writeUInt16LE | writeUInt16LE(value, offset[, noAssert])    |writeUInt16LE(value, offset=0, noAssert=false)|
|writeUInt32BE | writeUInt32BE(value, offset[, noAssert])    |writeUInt32BE(value, offset=0, noAssert=false)|
|writeUInt32LE | writeUInt32LE(value, offset[, noAssert])    |writeUInt32LE(value, offset=0, noAssert=false)|
|writeUIntBE   | writeUIntBE(value, offset, byteLength[, noAssert])|writeUIntBE(value, offset=0, noAssert=false)|
|writeUIntLE   | writeUIntLE(value, offset, byteLength[, noAssert])|writeUIntLE(value, offset=0, noAssert=false)|

| property |  Node.js v7 |    fibjs   |
|----------|-------------|------------|
| length   | buf.length  | length     |
| index    | buf[index]  | operator[] |
