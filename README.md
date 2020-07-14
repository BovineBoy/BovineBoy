### 🎸 & 🐛

```javascript
function myNew() {
  const Constructor = Array.prototype.shift.call(arguments)
  const obj = Object.create(Constructor.prototype)
  const result = Constructor.apply(obj, arguments)
  return result instanceof Object ? result : obj
}
```
