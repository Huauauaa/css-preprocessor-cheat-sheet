# scss

## init

`pnpm create vite scss_cheat_sheet -- --template vanilla`

## compile

`sass <input.scss> <output.css>`

## reference

- [https://mp.weixin.qq.com/s/m6dj8-Zg7W_sLheo4uTo8w](https://mp.weixin.qq.com/s/m6dj8-Zg7W_sLheo4uTo8w)

## Summary

- @function 用来计算，@mixin 用来封装样式，@import 用来抽离他们为一个模块。

### @import 缺点

- 多处导入，存在样式重复加载。
- 因为没有命名空间，为了避免撞名，不敢使用简写的 classname，因此起名总是需要注意。
- 没有私有函数的概念，样式完全暴露在使用 import 的地方，这对 ui 库不够友好。
