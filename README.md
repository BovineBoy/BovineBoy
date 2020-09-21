### 🎸 & 🐛

```javascript
function myNew() {
  const Constructor = Array.prototype.shift.call(arguments)
  const obj = Object.create(Constructor.prototype)
  const result = Constructor.apply(obj, arguments)
  return result instanceof Object ? result : obj
}
```

[![](https://github-readme-stats.vercel.app/api?username=BovineBoy&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)](https://github-readme-stats.vercel.app/api?username=BovineBoy&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)
