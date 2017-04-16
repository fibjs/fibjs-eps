# util

module

## method

|     API    |        Node.js v7          |                       fibjs                  |
|------------|----------------------------|--------------------------------------------- |
|debuglog |debuglog(section)||
|deprecate |deprecate(function, string)||
|format |format(format[, ...args])|format(String fmt,...), format(...)|
|inherits |inherits(constructor, superConstructor)| inherits(Value constructor, Value superConstructor)|
|inspect |inspect(object[, options])||
|inspect |inspect.custom||
|inspect |inspect.defaultOptions||
|_extend |_extend(target, source)||
|debug |debug(string)||
|error |error([...strings])||
|isEmpty ||isEmpty(Value v)|
|isArray |isArray(object)|isArray(Value v)|
|isBoolean |isBoolean(object)|isBoolean(Value v)|
|isBuffer |isBuffer(object)|isBuffer(Value v)|
|isDate |isDate(object)|isDate(Value v)|
|isError |isError(object)||
|isFunction |isFunction(object)|isFunction(Value v)|
|isNull |isNull(object)|isNull(Value v)|
|isNullOrUndefined |isNullOrUndefined(object)|isNullOrUndefined(Value v)|
|isNumber |isNumber(object)|isNumber(Value v)|
|isObject |isObject(object)|isObject(Value v)|
|isPrimitive |isPrimitive(object)||
|isRegExp |isRegExp(object)|isRegExp(Value v)|
|isString |isString(object)|isString(Value v)|
|isSymbol |isSymbol(object)||
|isUndefined |isUndefined(object)|isUndefined(Value v)|
|log |log(string)||
|print |print([...strings])||
|puts |puts([...strings])||
|has |   |Boolean has(Value v, String key)|
|keys |   |Array keys(Value v)|
|values |   |Array values(Value v)|
|clone |   |Value clone(Value v)|
|extend |   |Value extend(Value v,...)|
|pick |   |Object pick(Value v,...)|
|omit |   |Object omit(Value v,...)|
|first |   |Value first(Value v)|
|first |   |Value first(Value v, Integer n)|
|last |   |Value last(Value v)|
|last |   |Value last(Value v, Integer n)|
|unique |   |Array unique(Value v, Boolean sorted=false)|
|union |   |Array union(...)|
|intersection |   |Array intersection(...)|
|flatten |   |Array flatten(Value arr, Boolean shallow=false)|
|without |   |Array without(Value arr,...)|
|difference |   |Array difference(Array list,...)|
|each |   |Value each(Value list, Function iterator, Value context=undefined)|
|map |   |Array map(Value list, Function iterator, Value context=undefined)|
|reduce |   |Value reduce(Value list, Function iterator, Value memo, Value context=undefined)|
|buildInfo |   |Object buildInfo()|

## property

| property | Node.js v7| fibjs     |
|----------|-----------|-----------|
|Stats     |           | Stats     |
|LruCache  |           | LruCache  |
