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

| method | fibjs | Node.js|
|-----|-------|--------|
|listenerCount||EventEmitter.listenerCount(emitter, eventName)|

### method

| method | fibjs | Node.js|
|-----|-------|--------|
|addListener| Object 	addListener (String ev, Function func), Object 	addListener (Object map) |emitter.addListener(eventName, listener)|
|emit| Boolean 	emit (String ev,...) |emitter.emit(eventName[, ...args])|
|eventNames||emitter.eventNames()|
|getMaxListeners||emitter.getMaxListeners()|
|listenerCount||emitter.listenerCount(eventName)|
|listeners||emitter.listeners(eventName)|
|on|Object 	on (String ev, Function func), Object 	on (String ev, Function func)|emitter.on(eventName, listener)|
|once| Object 	once (String ev, Function func), Object 	once (Object map) |emitter.once(eventName, listener)|
|prependListener||emitter.prependListener(eventName, listener)|
|prependOnceListener||emitter.prependOnceListener(eventName, listener)|
|removeAllListeners| Object 	removeListener (String ev, Function func), Object 	removeListener (String ev),Object 	removeListener (Object map), Object 	removeAllListeners (Array evs=[]) |emitter.removeAllListeners([eventName])|
|removeListener||emitter.removeListener(eventName, listener)|
|setMaxListeners| setMaxListeners (Integer n) |emitter.setMaxListeners(n)|
|off|Object 	off (String ev, Function func), Object 	off (String ev), Object 	off (Object map)||
|listeners|Array 	listeners (String ev)||

### Event

| Event | fibjs | Node.js|
|-----|-------|--------|
|||newListener|
|||removeListener|

## property

| property | fibjs | Node.js|
|-----|-------|--------|
|||defaultMaxListeners|
