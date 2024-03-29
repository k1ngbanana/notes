## 书籍地址
[JavaScript 轻量级函数式编程](https://wizardforcel.gitbooks.io/functional-light-js/content/)

### 函数基础
- 在定义函数时，最好不要用 return 来实现流控制，这样会创造更多的隐含意义。
- 命名所有单个函数。如果你对着你写的函数，想不出一个好名称，我明确告诉你，那是你并没有完全理解这个函数的目的——或者来说它的目的太广泛或太抽象。你需要重新设计功能，直到它更清楚。从这个角度说，一个名称会更明白清晰。

### 减少副作用
- 引用透明性是指一个函数调用可以被它的输出值所代替，并且整个程序的行为不会改变。换句话说，不可能从程序的执行中分辨出函数调用是被执行的，还是它的返回值是在函数调用的位置上内联的。
