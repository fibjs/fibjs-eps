# assert

module

## method

|         API       |                    Node.js v7                  |  fibjs  |
|------------------ |------------------------------------------------|-------  |
|Function           | assert(value[, message])                       |Function (Value actual, String msg="") |
|deepEqual          | deepEqual(actual, expected[, message])         |deepEqual (Value actual, Value expected, String msg="") |
|deepStrictEqual    | deepStrictEqual(actual, expected[, message])   | |
|doesNotThrow       | doesNotThrow(block[, error][, message])        | doesNotThrow (Function block, String msg="")|
|equal              | equal(actual, expected[, message])             |equal (Value actual, Value expected, String msg="") |
|fail               | fail(actual, expected, message, operator)      | |
|ifError            | ifError(value)                                 |ifError(Value object = undefined) |
|notDeepEqual       | notDeepEqual(actual, expected[, message])      | notDeepEqual (Value actual, Value expected, String msg="")|
|notDeepStrictEqual | notDeepStrictEqual(actual, expected[, message])| |
|notEqual           | notEqual(actual, expected[, message])          |notEqual (Value actual, Value expected, String msg="") |
|notStrictEqual     | notStrictEqual(actual, expected[, message])    |notStrictEqual (Value actual, Value expected, String msg="") |
|notOk     |  | notOk (Value actual, String msg="")|
|ok                 | ok(value[, message])                           |ok (Value actual, String msg="") |
|strictEqual        | strictEqual(actual, expected[, message])       | strictEqual (Value actual, Value expected, String msg="")|
|throws             | throws(block[, error][, message])              | throws (Function block, String msg="") |
|closeTo||closeTo (Value actual, Value expected, Value delta, String msg="")|
|notCloseTo||notCloseTo (Value actual, Value expected, Value delta, String msg="")|
|lessThan||lessThan (Value actual, Value expected, String msg="")|
|notLessThan||notLessThan (Value actual, Value expected, String msg="")|
|greaterThan||greaterThan (Value actual, Value expected, String msg="")|
|notGreaterThan||notGreaterThan (Value actual, Value expected, String msg="")|
|exist||exist (Value actual, String msg="")|
|notExist||notExist (Value actual, String msg="")|
|isTrue||isTrue (Value actual, String msg="")|
|isNotTrue||isNotTrue (Value actual, String msg="") |
|isFalse||isFalse (Value actual, String msg="") |
|isNotFalse||isNotFalse (Value actual, String msg="") |
|isNull||isNull (Value actual, String msg="") |
|isNotNull||isNotNull (Value actual, String msg="") |
|isUndefined||isUndefined (Value actual, String msg="") |
|isDefined||isDefined (Value actual, String msg="") |
|isFunction||isFunction (Value actual, String msg="") |
|isNotFunction||isNotFunction (Value actual, String msg="") |
|isObject||isObject (Value actual, String msg="") |
|isNotObject||isNotObject (Value actual, String msg="") |
|isArray||isArray (Value actual, String msg="") |
|isNotArray||isNotArray (Value actual, String msg="") |
|isString||isString (Value actual, String msg="") |
|isNotString||isNotString (Value actual, String msg="") |
|isNumber||isNumber (Value actual, String msg="") |
|isNotNumber||isNotNumber (Value actual, String msg="") |
|isBoolean||isBoolean (Value actual, String msg="") |
|isNotBoolean||isNotBoolean (Value actual, String msg="") |
|typeOf||typeOf (Value actual, String type, String msg="") |
|notTypeOf||notTypeOf (Value actual, String type, String msg="") |
|property||property (Value object, Value prop, String msg="") |
|notProperty||notProperty (Value object, Value prop, String msg="") |
|deepProperty||deepProperty (Value object, Value prop, String msg="") |
|notDeepProperty||notDeepProperty (Value object, Value prop, String msg="") |
|propertyVal||propertyVal (Value object, Value prop, Value value, String msg="") |
|propertyNotVal||propertyNotVal (Value object, Value prop, Value value, String msg="") |
|deepPropertyVal||deepPropertyVal (Value object, Value prop, Value value, String msg="") |
|deepPropertyNotVal||deepPropertyNotVal (Value object, Value prop, Value value, String msg="")| 
