Function.prototype.apply5 = function(context) {
    context = context || window
    const fn = Symbol()
    context[fn] = this
    let res
    if (arguments.length > 1) {
      res = context[fn](...arguments[1])
    } else {
      res = context[fn]()
    }

    delete context[fn]
    return res
}

Function.prototype.call5 = function(context) {
    context = context || window
    const fn = Symbol()
    context[fn] = this
    let res
    if (arguments.length > 1) {
      const [, ...args] = arguments
      res = context[fn](...args)
    } else {
      res = context[fn]()
    }

    delete context[fn]
    return res
}

var obj = {
    name: 'jawil'
}

function sayHello(age, sex) {
    return {
        name: this.name,
        age: age,
        sex,
    }
}

console.log(sayHello.call5(obj, 23, '男'))
console.log(sayHello.apply5(obj, [23, '男']))
