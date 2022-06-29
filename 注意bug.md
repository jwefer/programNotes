## 1. 调用hasOwnProperty判断对象是否包含某属性出错

解决方法：使用`Object.prototype.hasOwnProperty.call(obj, 'xxx')`来代替`obj.hasOwnProperty('xxx')`