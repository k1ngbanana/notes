## 类型转换
1. undefined和null
`undefined -> NaN`, `null -> 0`
null和undefined在==中相等，和其他值都不等
``` ts
null == undefined // true
null > 0 // false
null == 0 // false
null >= 0 // true
```
1. 对象对比
``` ts
const a = { b: 42 }
const b = { b: 43 }

a < b // false
a == b // false -> 内存地址比较
a > b // false

a <= b // true -> !(a > b)
a >= b // true -> !(a < b)
```
