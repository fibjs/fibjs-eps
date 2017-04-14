# fibjs 与 Node 基础运行机制差异点

## Stream API

### fibjs
  同步API
- 读

```js
readFrom(con)
```

- 写

```js
sendTo(con)
```

### Node.js

异步API

- 读

```js
steam.on('data', data => {

});
```

- 写

```js
steam.pipe(data)
```

## 内置对象

### fibjs

内置对象为C++对象，不可以随意修改

### Node.js

内置对象大多为JS对象，可以随意修改
