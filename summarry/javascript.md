# JavaScript题目汇总

# 全部面试题汇总

### 写一个 mySetInterVal(fn, a, b),每次间隔 a,a+b,a+2b 的时间，然后写一个 myClear，停止上面的 mySetInterVal

公司：头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/7)

<br/>

### 介绍防抖节流原理、区别以及应用，并用JavaScript进行实现

公司：滴滴、虎扑、挖财、58、头条

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/15)

<br/>

### 对闭包的看法，为什么要用闭包？说一下闭包原理以及应用场景

公司：滴滴、携程、喜马拉雅、微医、蘑菇街、酷家乐、腾讯应用宝、安居客

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/17)

<br/>

### 实现 lodash 的_.get

公司：滴滴

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/20)

<br/>

### 实现 add(1)(2)(3)

公司：滴滴

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/21)

<br/>

### 实现链式调用

公司：滴滴

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/22)

<br/>

### 类数组和数组的区别，dom 的类数组如何转换成数组

公司：海康威视

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/24)

<br/>

### 介绍下 promise 的特性、优缺点，内部是如何实现的，动手实现 Promise

公司：滴滴、头条、喜马拉雅、兑吧、寺库、百分点、58、安居客

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/29)

<br/>

### 实现 Promise.all

```js
Promise.all = function (arr) {
  // 实现代码
};
```

公司：滴滴、头条、有赞、微医

分类：JavaScript、编程题

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/30)

<br/>

### 手写发布订阅

公司：滴滴、头条

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/34)

<br/>

### 手写数组转树

公司：滴滴

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/35)

<br/>

### 手写用 ES6proxy 如何实现 arr[-1] 的访问

公司：滴滴

分类：JavaScript

[答案&解析](https://github.com/lgwebdream/FE-Interview/issues/36)

<br/>

### 手写实现 Array.flat()

公司：滴滴、快手、携程

分类：JavaScript

[答案&解析]()

<br/>

### 大数计算如何实现

公司：洋葱学院

分类：JavaScript

[答案&解析]()

<br/>

### 什么是深拷贝，和浅拷贝有什么区别，动手实现一个深拷贝

公司：顺丰、新东方、高德、虎扑、微医、百分点、酷狗、新东方

分类：JavaScript

[答案&解析]()

<br/>

### 实现一个方法判断 html 中的标签是否闭合

分类：JavaScript

[答案&解析]()

<br/>

### 箭头函数和普通函数的区别

公司：酷家乐

分类：JavaScript

[答案&解析]()

<br/>

### es5 实现 isInteger

公司：头条

分类：JavaScript

[答案&解析]()

<br/>

### 写出输出结果

```js
function Foo() {
  getName = function () {
    alert(1);
  };
  return this;
}
var getName;
function getName() {
  alert(5);
}
Foo.getName = function () {
  alert(2);
};
Foo.prototype.getName = function () {
  alert(3);
};
getName = function () {
  alert(4);
};

Foo.getName(); // ？
getName(); // ？
Foo().getName(); // ？
getName(); // ？
new Foo.getName(); // ?
new Foo().getName(); // ?
new new Foo().getName(); // ？
```

公司：心娱

分类：JavaScript

[答案&解析]()

<br/>

### 手写 dom 操作，翻转 li 标签，如何处理更优

```js
/*
 *有下边这样的dom结构，现在可以获取到ul，要求翻转里边li标签，如何处理更优
 */
<ul>
  <li>1</li>
  <li>2</li>
  <li>3</li>
</ul>
```

公司：快手

分类：

[答案&解析]()

<br/>

### 怎样判断一个对象是否是数组，如何处理类数组对象

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 是否了解 glob，glob 是如何处理文件的，业界是否还有其它解决方案

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 随便打开一个网页，用 JavaScript 打印所有以 s 和 h 开头的标签，并计算出标签的种类

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 1000\*1000 的画布，上面有飞机、子弹，如何划分区域能够更有效的做碰撞检测，类似划分区域大小与碰撞检测效率的算法，说一下大致的思路

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 移动设备安卓根 iOS 的软键盘弹出的处理方式有什么不同

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### iPhone 里面 Safari 上如果一个输入框 fixed 绝对定位在底部，当软键盘弹出的时候会有什么问题，如何解决

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 给定一个数组，按找到每个元素右侧第一个比它大的数字，没有的话返回-1 规则返回一个数组

```js
/*
 *示例：
 *给定数组：[2,6,3,8,10,9]
 *返回数组：[6,8,8,10,-1,-1]
 */
```

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 说一说 promise，有几个状态，通过 catch 捕获到 reject 之后，在 catch 后面还能继续执行 then 方法嘛，如果能执行执行的是第几个回调函数

公司：伴鱼、喜马拉雅

分类：JavaScript

[答案&解析]()

<br/>

### var、let、const 的区别

公司：伴鱼、百分点、心娱

分类：JavaScript

[答案&解析]()

<br/>

### 说一下 GC

公司：伴鱼

分类：JavaScript

[答案&解析]()

<br/>

### 如何实现按需加载

公司：伴鱼、腾讯应用宝

分类：JavaScript

[答案&解析]()

<br/>

### 讲一下 import 的原理，与 require 有什么不同

公司：伴鱼、腾讯应用宝

分类：JavaScript

[答案&解析]()

<br/>

### 请实现如下的函数

```js
/*
	可以批量请求数据，所有的 URL 地址在 urls 参数中，同时可以通过 max 参数控制请求的并发度，当所有请求结束之后，需要执行 callback 回调函数。发请求的函数可以直接使用 fetch 即可
*/
```

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 是否用过 restful 接口，和其他风格的有什么区别

公司：边锋

分类：JavaScript

[答案&解析]()

<br/>

### 说一下 get、post、put 的区别

公司：边锋、虎扑、酷家乐、酷狗、安居客

分类：JavaScript

[答案&解析]()

<br/>

### 说一下对面向对象的理解，面向对象有什么好处

公司：边锋

分类：JavaScript

[答案&解析]()

<br/>

### 类设计：使用面相对象设计一个停车场管理系

```js
/*
 *题目要求
 *使用面相对象设计一个停车场管理系统，该停车场包含：
 *	1.停车位，用于停放车辆；
 *	2.停车位提示牌，用于展示剩余停车位；
 *可以丰富该系统的元素，给出类，类属性，类接口。
 */
```

公司：边锋

分类：JavaScript

[答案&解析]()

<br/>

### 实现输出一个十六进制的随机颜色(#af0128a)

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### justify-content:space-between around 有什么区别

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 手写代码实现`kuai-shou-front-end=>KuaiShouFrontEnd`

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 设计一个 Student 组件，实现输入姓名性别成绩（这三个必填），还有几个不是必填的属性，要设置默认值，点击弹出成绩

公司：老虎

分类：JavaScript

[答案&解析]()

<br/>

### 设计一个函数，奇数次执行的时候打印 1，偶数次执行的时候打印 2

公司：老虎

分类：JavaScript

[答案&解析]()

<br/>

### 实现 Promise.then

公司：高德、百分点

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 平时在项目开发中都做过哪些前端性能优化

公司：阿里、顺丰、易车、有赞、挖财、喜马拉雅、兑吧、寺库、海康威视、道一云、58

分类：JavaScript

[答案&解析]()

<br/>

### 给定起止日期，返回中间的所有月份

```js
// 输入两个字符串 2018-08  2018-12
// 输出他们中间的月份 [2018-10, 2018-11]
```

公司：顺丰

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 输入两个字符串，输出他们中间的月份

```js
// 给两个数组 [A1,A2,B1,B2,C1,C2,D1,D2] [A,B,C,D]
// 输出 [A1,A2,A,B1,B2,B,C1,C2,C,D1,D2,D]
```

公司：顺丰

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 用尽量短的代码实现一个 arrary 的链式操作，将数组中的大于 10 的值进行一个累加

公司：顺丰

分类：JavaScript

[答案&解析]()

<br/>

### 简单封装一个异步 fecth，使用 async await 的方式来使用

公司：顺丰

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请写一个函数，输出出多级嵌套结构的 Object 的所有 key 值

```js
var obj = {
  a: "12",
  b: "23",
  first: {
    c: "34",
    d: "45",
    second: { 3: "56", f: "67", three: { g: "78", h: "89", i: "90" } },
  },
};
// => [a,b,c,d,e,f,g,h,i]
```

公司：顺丰

分类：JavaScript、编程题

[答案&解析]()

<br/>



### 写出打印结果，并解释为什么

```js
var a = { k1: 1 };
var b = a;
a.k3 = a = { k2: 2 };
console.log(a); // ?
console.log(b); // ?
```

公司：头条

分类：JavaScript

[答案&解析]()

<br/>

### 动手实现一个 repeat 方法

```js
function repeat(func, times, wait) {
  // TODO
}
const repeatFunc = repeat(alert, 4, 3000);
// 调用这个 repeatFunc ("hellworld")，会alert4次 helloworld, 每次间隔3秒
```

公司：头条

分类：JavaScript、编程题

[答案&解析]()

<br/>

### setTimeout 有什么缺点，和 requestAnimationFrame 有什么区别

公司：头条

分类：JavaScript

[答案&解析]()

<br/>

### versions 是一个项目的版本号列表，因多人维护，不规则，动手实现一个版本号处理函数

```js
var versions = ["1.45.0", "1.5", "6", "3.3.3.3.3.3.3"];
// 要求从小到大排序，注意'1.45'比'1.5'大
function sortVersion(versions) {
  // TODO
}
// => ['1.5','1.45.0','3.3.3.3.3.3','6']
```

公司：头条

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 实现一个多并发的请求

```js
let urls = ['http://dcdapp.com', …];
/*
	*实现一个方法，比如每次并发的执行三个请求，如果超时（timeout）就输入null，直到全部请求完
	*batchGet(urls, batchnum=3, timeout=3000);
	*urls是一个请求的数组，每一项是一个url
	*最后按照输入的顺序返回结果数组[]
*/
```

公司：头条

分类：JavaScript

[答案&解析]()

<br/>

### 写出代码执行结果

```js
async function async1() {
  console.log("async1 start");
  await async2();
  console.log("async1 end");
}
async function async2() {
  console.log("async2");
}
console.log("script start");
setTimeout(function () {
  console.log("setTimeout");
}, 0);
async1();
new Promise(function (resolve) {
  console.log("promise1");
  resolve();
}).then(function () {
  console.log("promise2");
});
console.log("scripts end");
// 写出代码执行完成打印的结果
```

公司：头条、网易

分类：JavaScript

[答案&解析]()

<br/>

### 按要求实现一个 sum 函数

```js
const a = sum(); // => a === 0
const b = sum(); // => b === 2
const c = sum(4)(5); // c === 9
const k = sum(n1)...(nk) // k === n1 + n2 + ... + nk
```

公司：头条

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 说一下 base64 的编码方式

公司：完美世界

分类：JavaScirpt

[答案&解析]()

<br/>

### 改变 this 指向的方式都有哪些？

公司：网易

分类：JavaScript

[答案&解析]()

<br/>

### 说一下`module.exports`和`exports`的区别，`export`和`export default`的区别

公司：网易

分类：JavaScript

[答案&解析]()

<br/>

### number 为什么会出现精度损失，怎样避免

公司：网易

分类：JavaScript

[答案&解析]()

<br/>

### 实现一个函数将中文数字转成数字

公司：微软

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 节流

公司：微软

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 如何实现 5 秒自动刷新一次页面(具体都有什么方法 reload 之类的)

公司：易车

分类：JavaScript

[答案&解析]()

<br/>

### 都了解哪些 ES6、ES7 的新特性，箭头函数可以被 new 吗

公司：易车、脉脉、虎扑、喜马拉雅、百分点、海风教育、58

分类：JavaScript

[答案&解析]()

<br/>

### 说一下 JavaScript 继承都有哪些方法

公司：易车、脉脉、微医、海康威视

分类：JavaScript

[答案&解析]()

<br/>

### 已知函数 A，要求构造⼀个函数 B 继承 A

```js
function A(name) {
  this.name = name;
}
A.prototype.getName = function () {
  console.log(this.name);
};
```

公司：新东方

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 数组和对象转换为字符串结果

```js
var arry = [];
var obj = {};
// arry,obj 转成字符串的结果是什么？
```

公司：新东方

分类：JavaScript

[答案&解析]()

<br/>

### 请写出以下代码的打印结果

```js
var a = {
  name: "A",
  fn() {
    console.log(this.name);
  },
};
a.fn();
a.fn.call({ name: "B" });
var fn1 = a.fn;
fn1();
// 写出打印结果
```

公司：新东方

分类：JavaScript

[答案&解析]()

<br/>

### 请写出以下代码的打印结果

```js
let int = 1;
setTimeout(function () {
  console.log(int);
  int = 2;
  new Promise((resolve, reject) => {
    resolve();
  }).then(function () {
    console.log(int);
    int = 7;
  });
  console.log(int);
});
int = 3;
console.log(int);
new Promise((resolve, reject) => {
  console.log(int);
  return resolve((int = 4));
}).then(function (res) {
  console.log(int);
  int = 5;
  setTimeout(function () {
    console.log(int);
    int = 8;
  });
  return false;
});
console.log(int);
// 写出打印结果
```

公司：新东方

分类：JavaScript

[答案&解析]()

<br/>

### 要求⽤不同⽅式对 A 进⾏改造实现 A.name 发⽣变化时⽴即执⾏ A.getName

```js
/*
	已知对象A = {name: 'sfd', getName: function(){console.log(this.name)}},
	现要求⽤不同⽅式对A进⾏改造实现A.name发⽣变化时⽴即执⾏A.getName
*/
```

公司：新东方

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 修改以下代码，使得最后⼀⾏代码能够输出数字 0-9（最好能给多种答案）

```js
var arrys = [];
for (var i = 0; i < 10; i++) {
  arrys.push(function () {
    return i;
  });
}
arrys.forEach(function (fn) {
  console.log(fn());
}); //本⾏不能修改
```

公司：新东方

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请给出识别 Email 的正则表达式

公司：头条

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 设计 AutoComplete 组件(又叫搜索组件、自动补全组件等)时，需要考虑什么问题？

公司：头条

分类：JavaScript

[答案&解析]()

<br/>

### 实现函数接受任意二叉树，求二叉树所有根到叶子路径组成的数字之和

```js
class TreeNode{
  value:number
  left?:TreeNode
  right?:TreeNode
}
function getPathSum(root){
  // your code
}
// 例子，一层二叉树如下定义，路径包括1 —> 2 ,1 -> 3
const node = new TreeNode();
node.value = 1;
node.left = new TreeNode();
node.left.value = 2;
node.right = new TreeNode();
node.right.value = 3;
getPathSum(node); // return 7 = (1+2) + (1+3)
```

公司：头条

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请写出一下代码的打印结果

```js
function a(obj) {
  obj.a = 2;
  obj = { a: 3 };
  return obj;
}
const obj = { a: 1 };
a(obj);
console.log(obj);
```

公司：滴滴

分类：JavaScript

[答案&解析]()

<br/>

### Promise 链式调用如何实现

公司：滴滴

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 说一下对`BigInt`的理解，在什么场景下会使用

公司：滴滴、高德

分类：JavaScript

[答案&解析]()

<br/>

### null 是不是一个对象，如果是，如何判断一个对象是 null，不使用 JavaScript 提供的 api 如何进行判断

公司：滴滴

分类：JavaScript

[答案&解析]()

<br/>

### 说一下对于堆栈的理解

公司：滴滴、高德

分类：JavaScript

[答案&解析]()

<br/>

### `[] == ![]`为什么

公司：高德

分类：JavaScript

[答案&解析]()

<br/>

### 如何把真实 dom 转变为虚拟 dom，代码实现一下

公司：高德

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 说一下错误监控的实现，错误监控的正确使用方式，日志如何分等级

公司：高德

分类：JavaScript

[答案&解析]()

<br/>

### 请写出以下代码执行结果

```js
var a = { x: 1 };
var b = a;
a.x = a = { n: 1 };
console.log(a); // ?
console.log(b); // ?
```

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 请写出以下代码执行结果

```js
Function.prototype.a = () = >{alert(1)}
Object.prototype.b = () = >{alert(2)}
function A(){};
const a = new A();
a.a();
a.b();
// 写出执行结果
```

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 请写出以下代码执行结果

```js
let a = 0;
console.log(a);
console.log(b);
let b = 0;
console.log(c);
function c() {}
// 写出执行结果
```

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 请写出以下代码执行结果

```js
var x = 10;
function a(y) {
  var x = 20;
  return b(y);
}
function b(y) {
  return x + y;
}
a(20);
// 写出执行结果
```

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 请写出以下代码执行结果

```js
console.log(1);
setTimeout(() => {
  console.log(2);
});
process.nextTick(() => {
  console.log(3);
});
setImmediate(() => {
  console.log(4);
});
new Promise((resolve) => {
  console.log(5);
  resolve();
  console.log(6);
}).then(() => {
  console.log(7);
});
Promise.resolve().then(() => {
  console.log(8);
  process.nextTick(() => {
    console.log(9);
  });
});
// 写出执行结果
```

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 请写出以下代码执行结果

```js
[1, 2, 3, 4, 5].map(parselnt);
// 写出执行结果
```

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 请写出以下代码执行结果

```js
typeof typeof typeof [];
// 写出执行结果
```

公司：快手

分类：JavaScript

[答案&解析]()

<br/>



### 说一下什么是死锁

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 实现以下代码

```js
function add() {
  // your code
}
function one() {
  // your code
}
function two() {
  // your code
}
console.log(add(one(two()))); //3
console.log(add(two(one()))); //3
```

公司：快手

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请实现一个 cacheRequest 方法，保证发出多次同一个 ajax 请求时都能拿到数据，而实际上只发出一次请求

公司：快手

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 实现一个函数柯里化

公司：快手

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 说一下对原型链的理解，画一个经典的原型链图示

公司：脉脉、兑吧、快手

分类：JavaScript

[答案&解析]()

<br/>

### 说一下 ajax/axios/fetch 的区别

公司：脉脉

分类：JavaScript

[答案&解析]()

<br/>

### 用 Promise 封装一个 ajax

公司：脉脉

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 描述 DOM 事件捕获的具体流程

公司：自如

分类：JavaScript

[答案&解析]()

<br/>

### 请实现`$on,$emit`

公司：自如

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 实现 bind 方法，不能使用 call、apply、bind

公司：自如、腾讯应用宝、快手

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 手写实现 sleep 函数

公司：自如

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请写出原生 js 如何设置元素高度

公司：自如

分类：JavaScript

[答案&解析]()

<br/>

### 用原生 js 实现自定义事件

公司：自如

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 换行字符串格式化

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 输入一个日期 返回几秒前、几小时前、几天前、几月前

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 将 153812.7 转化为 153,812.7

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 数组有哪些方法 讲讲区别跟使用场景

公司：掌门一对一

分类：JavaScript

[答案&解析]()

<br/>

### 讲一下函数式编程

公司：掌门一对一

分类：JavaScript

[答案&解析]()

<br/>

### promise 跟 async await 的区别，使用场景 

公司：网易、虎扑、沪江

分类：JavaScript

[答案&解析]()

<br/>

### async、await 如何进行错误捕获

公司：虎扑

分类：JavaScript

[答案&解析]()

<br/>

### weak-Set、weak-Map 和 Set、Map 区别

公司：虎扑

分类：JavaScript

[答案&解析]()

<br/>

### valueOf 与 toString 的区别

分类：JavaScript

[答案&解析]()

<br/>

### 怎么判断是一个空对象

公司：菜鸟网络

分类：JavaScript

[答案&解析]()

<br/>

### 请写出下面代码的执行结果

```js
setTimeout(() => {
  console.log(0);
}, 0);
new Promise((res) => setTimeout(res, 0)).then(() => {
  console.log(1);
  setTimeout(() => {
    console.log(2);
  }, 0);
  new Promise((r = r())).then(() => {
    console.log(3);
  });
});
setTimeout(() => {
  console.log(4);
}, 0);
new Promise((res) => res()).then(() => {
  console.log(5);
});
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出下面代码的执行结果

```js
function Foo() {
  getName = function () {
    alert(1);
  };
  return this;
}
getName();
Foo.getName = function () {
  alert(2);
};
Foo.prototype.getName = function () {
  alert(3);
};
getName = function () {
  alert(4);
};

// 请写出下面的输出结果
getName90;
Foo.getName();
new Foo().getName();
```

分类：JavaScript

[答案&解析]()

<br/>

### 请只用数组方法和 Math.random()在一条语句的情况下，实现生成给定位数的随机数组，例如生成 10 位随机数组[1.1,102.1,2,3,8,4,90,123,11,123],数组内数字随机生成。

分类：JavaScript

[答案&解析]()

<br/>

### 实现一个 setter 方法

```js
let setter = function (conten, key, value) {
  // your code
};
let n = {
  a: {
    b: {
      c: { d: 1 },
      bx: { y: 1 },
    },
    ax: { y: 1 },
  },
};
// 修改值
setter(n, "a.b.c.d", 3);
console.log(n.a.b.c.d); //3
setter(n, "a.b.bx", 1);
console.log(n.b.bx); //1
```

分类：JavaScript、编程题

[答案&解析]()

<br/>

### setTimeout 与 setInterval 区别

公司：腾讯应用宝

分类：JavaScript

[答案&解析]()

<br/>

### 项目中如何应用数据结构

公司：挖财

分类：JavaScript

[答案&解析]()

<br/>

### 闭包的核心是什么

公司：寺库

分类：JavaScript

[答案&解析]()

<br/>

### 写出代码输出结果

```js
var fullname = "Test1";
var obj = {
  fullname: "Test2",
  prop: {
    fullname: "Test3",
    getFullname: function () {
      return this.fullname;
    },
  },
};
console.log(obj.prop.getFullname());
var test = obj.prop.getFullname;
console.log(test());
```

公司：心娱、安居客

分类：JavaScript

[答案&解析]()

<br/>

### 实现一个功能，发送请求 5s 时间后，如果没有数据返回，中断请求,提示错误

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 什么是作用域链

分类：JavaScript

[答案&解析]()

<br/>

### 介绍事件冒泡、事件代理、事件捕获，以及它们的关系

公司：腾讯应用宝、安居客

分类：JavaScript

[答案&解析]()

<br/>

### for..of 和 for...in 是否可以直接遍历对象，为什么

分类：JavaScript

[答案&解析]()

<br/>

### 在 map 中和 for 中调用异步函数的区别

分类：JavaScript

[答案&解析]()

<br/>

### gennerator yield 的作用

分类：JavaScript

[答案&解析]()

<br/>

### promise 的状态有哪些

公司：微医

分类：JavaScript

[答案&解析]()

<br/>

### 在 ES6 中有哪些解决异步的方法

分类：JavaScript

[答案&解析]()

<br/>

### es6 类继承中 super 的作用

分类：JavaScript

[答案&解析]()

<br/>

### cros 的简单请求和复杂请求的区别

分类：JavaScript

[答案&解析]()

<br/>

### addEventListener 的第三个参数的作用

分类：JavaScript

[答案&解析]()

<br/>

### 获取 id 为 netease 节点下所有的 checkbox 子元素(不用框架，注意兼容)

公司：网易

分类：JavaScript

[答案&解析]()

<br/>

### 使用原型链如何实现继承

公司：腾讯应用宝、安居客

分类：JavaScript

[答案&解析]()

<br/>

### 如何获取一个对象的深度

分类：JavaScript

[答案&解析]()

<br/>

### reduce 函数的功能，如何实现的，动手实现一下

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 说一下 splice 和 slice 的功能用法

分类：JavaScript

[答案&解析]()

<br/>

### 面向对象的三要素是啥？都是啥意思？

分类：JavaScript

[答案&解析]()

<br/>

### 函数中的 thisy 有几种

分类：JavaScript

[答案&解析]()

<br/>

### 如何同时获取 html 中的 h1,h2,h3,h4,h5,h6 中的内容

分类：JavaScript

[答案&解析]()

<br/>

### JavaScript 的执行流程

分类：JavaScript

[答案&解析]()

<br/>

### Promise.resolve(obj)，obj 有几种可能

分类：JavaScript

[答案&解析]()

<br/>

### 写出代码执行结果

```js
new Promise((resolve, reject) => {
  reject("1");
})
  .catch((e) => {
    console.log(1);
  })
  .then((res) => {
    console.log(2);
  });
```

分类：JavaScript

[答案&解析]()

<br/>

### nextTick 是在本次循环执行，还是在下次，setTimeout(() => {}, 0)呢？

分类：JavaScript

[答案&解析]()

<br/>

### 使用正则去掉 Dom 中的内联样式

分类：JavaScript

[答案&解析]()

<br/>

### 写一个匹配 ip 地址的正则

分类：JavaScript

[答案&解析]()

<br/>

### 写一个匹配 Html 标签的正则

分类：JavaScript

[答案&解析]()

<br/>

### IOC 是啥，应用场景是啥？

分类：JavaScript

[答案&解析]()

<br/>

### 写出代码执行的打印结果

```js
function a(obj) {
  obj.a = 2;
  obj = { a: 3 };
  return obj;
}
const obj = { a: 1 };
a(obj);
console.log(obj);
```

分类：JavaScript

[答案&解析]()

<br/>

### 实现函数

```js
d1,,,
d2,,,
d3,,,

把上边的字符串输出1，2，3的和 //6
```

分类：JavaScript

[答案&解析]()

<br/>

### 怎么实现 this 对象的深拷贝

公司：阿里

分类：JavaScript

[答案&解析]()

<br/>

### 使用 canvas 绘图时如何组织成通用组件

公司：宝宝树

分类：JavaScript

[答案&解析]()

<br/>

### 表单可以跨域吗

公司：网易

分类：JavaScript

[答案&解析]()

<br/>

### 搜索请求如何处理？搜索请求中文如何请求？

公司：网易

分类：JavaScript

[答案&解析]()

<br/>

### 介绍观察者模式

公司：网易、海风教育

分类：JavaScript

[答案&解析]()

<br/>

### 介绍中介者模式

公司：网易

分类：JavaScript

[答案&解析]()

<br/>

### 观察者和订阅-发布的区别，各自用在哪里

公司：网易、有赞、微医

分类：JavaScript

[答案&解析]()

<br/>

### 通过什么做到并发请求

公司：网易

分类：JavaScript

[答案&解析]()

<br/>

### 介绍 service worker

公司：网易

分类：JavaScript

[答案&解析]()

<br/>

### 介绍事件代理以及优缺点，主要解决什么问题

公司：网易、沪江

分类：JavaScript

[答案&解析]()

<br/>

### 介绍下 this 的各种情况

公司：网易、蘑菇街

分类：JavaScript

[答案&解析]()

<br/>

### 前端如何控制管理路由

公司：网易

分类：JavaScript

[答案&解析]()

<br/>

### 使用路由时出现问题如何解决

公司：网易

分类：JavaScript

[答案&解析]()

<br/>

### JavaScript 异步解决方案的发展历程以及优缺点

公司：滴滴、挖财、宝宝树、海康威视

分类：JavaScript

[答案&解析]()

<br/>

### 介绍 AST（Abstract Syntax Tree）抽象语法树

公司：滴滴

分类：JavaScript

[答案&解析]()

<br/>

### 对 async、await 的理解，内部原理是怎样的？

公司：头条

分类：JavaScript

[答案&解析]()

<br/>

### == 和 ===的区别，什么情况下用相等==

公司：头条、安居客

分类：JavaScript

[答案&解析]()

<br/>

### bind、call、apply 的区别

公司：头条、挖财、饿了么、心娱

分类：JavaScript

[答案&解析]()

<br/>

### 介绍下原型链

公司：头条

分类：JavaScript

[答案&解析]()

<br/>

### 介绍暂时性死区

公司：有赞

分类：JavaScript

[答案&解析]()

<br/>

### ES6 中的 map 和原生的对象有什么区别

公司：有赞

分类：JavaScript

[答案&解析]()

<br/>

### 对纯函数的理解

公司：有赞

分类：JavaScript

[答案&解析]()

<br/>

### 介绍 JSX

公司：有赞

分类：JavaScript

[答案&解析]()

<br/>

### 如何设计一个 localStorage，保证数据的实效性

公司：有赞

分类：JavaScript

[答案&解析]()

<br/>

### 实现 sum 方法，使 sum(x)(y),sum(x,y)返回的结果相同

公司：有赞、网易、乘法云

分类：JavaScript

[答案&解析]()

<br/>

### 两个对象如何比较

公司：有赞

分类：JavaScript

[答案&解析]()

<br/>

### 说一下变量的作用域链

公司：挖财

分类：JavaScript

[答案&解析]()

<br/>

### 介绍 dom 树对比

公司：挖财

分类：JavaScript

[答案&解析]()

<br/>

### 如何设计状态树

公司：挖财

分类：JavaScript

[答案&解析]()

<br/>

### Ajax 发生跨域要设置什么（前端）

公司：沪江

分类：JavaScript

[答案&解析]()

<br/>

### 加上 CORS 之后从发起到请求正式成功的过程

公司：沪江

分类：JavaScript

[答案&解析]()

<br/>

### Async 里面有多个 await 请求，可以怎么优化

公司：沪江

分类：JavaScript

[答案&解析]()

<br/>

### JavaScript 变量类型分为几种，区别是什么

公司：沪江、酷狗

分类：JavaScript

[答案&解析]()

<br/>

### JavaScript 里垃圾回收机制是什么，常用的是哪种，怎么处理的

公司：沪江、寺库

分类：JavaScript

[答案&解析]()

<br/>

### 小程序里面可以打开的页面是多少

公司：饿了么

分类：小程序

[答案&解析]()

<br/>

### ES5 和 ES6 有什么区别

公司：饿了么

分类：JavaScript

[答案&解析]()

<br/>

### 取数组的最大值（ES5、ES6）

公司：饿了么

分类：JavaScript

[答案&解析]()

<br/>

### some、every、find、filter、map、forEach 有什么区别

公司：饿了么

分类：JavaScript

[答案&解析]()

<br/>

### 页面上生成一万个 button，并且绑定事件，如何做（JS 原生操作 DOM）？循环绑定时的 index 是多少，为什么，怎么解决？

公司：饿了么

分类：JavaScript

[答案&解析]()

<br/>

### 页面上有一个 input，还有一个 p 标签，改变 input 后 p 标签就跟着变化，如何处理？监听 input 的哪个事件，在什么时候触发？

公司：饿了么

分类：JavaScript

[答案&解析]()

<br/>

### Promise 和 async/await，和 Callback 有什么区别

公司：携程、海风教育

分类：JavaScript

[答案&解析]()

<br/>

### 项目中对于用户体验做过什么优化

公司：喜马拉雅

分类：JavaScript

[答案&解析]()

<br/>

### 前后端通信使用什么方案

公司：喜马拉雅

分类：JavaScript

[答案&解析]()

<br/>

### RESTful 常用的 Method

公司：喜马拉雅

分类：JavaScript

[答案&解析]()

<br/>

### prototype 和**proto**区别

公司：兑吧

分类：JavaScript

[答案&解析]()

<br/>

### new 的实现原理，动手实现一个 new

公司：兑吧

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 如何实现 H5 手机端的适配

公司：兑吧、网易、心娱

分类：JavaScript

[答案&解析]()

<br/>

### 如何去除 url 中的#号

公司：兑吧

分类：JavaScript

[答案&解析]()

<br/>

### base64 为什么能提升性能，缺点

公司：兑吧

分类：JavaScript

[答案&解析]()

<br/>

### 介绍 webp 这个图片文件格式

公司：兑吧

分类：JavaScript

[答案&解析]()

<br/>

### 介绍 koa2，原理是什么？

公司：兑吧、海风教育

分类：JavaScript

[答案&解析]()

<br/>

### 异步请求，低版本 fetch 如何低版本适配

公司：兑吧

分类：JavaScript

[答案&解析]()

<br/>

### ajax 如何处理跨域？CORSr 如何设置？

公司：兑吧

分类：JavaScript

[答案&解析]()

<br/>

### jsonp 为什么不支持 post 方法

公司：兑吧

分类：JavaScript

[答案&解析]()

<br/>

### 介绍 Immuable

公司：兑吧

分类：JavaScript

[答案&解析]()

<br/>

### 介绍 JS 全部数据类型，基本数据类型和引用数据类型的区别

公司：微医、玄武科技、快手

分类：JavaScript

[答案&解析]()

<br/>

### Array 是 Object 类型吗

公司：微医

分类：JavaScript

[答案&解析]()

<br/>

### 说一下栈和堆的区别，垃圾回收时栈和堆的区别

公司：微医、寺库

分类：JavaScript

[答案&解析]()

<br/>

### 数组里面有 10 万个数据，取第一个元素和第 10 万个元素的时间相差多少

公司：微医

分类：JavaScript

[答案&解析]()

<br/>

### Async/Await 怎么实现

公司：微医

分类：JavaScript

[答案&解析]()

<br/>

### JavaScript 为什么要区分微任务和宏任务

公司：微医

分类：JavaScript

[答案&解析]()

<br/>

### Promise 构造函数是同步还是异步执行，then 呢

公司：微医

分类：JavaScript

[答案&解析]()

<br/>

### JavaScript 执行过程分为哪些阶段

公司：微医

分类：JavaScript

[答案&解析]()

<br/>

### 词法作用域和 this 的区别

公司：微医

分类：JavaScript

[答案&解析]()

<br/>

### loadsh 深拷贝实现原理

公司：微医

分类：JavaScript

[答案&解析]()

<br/>

### ES6 中 let 块作用域是怎么实现的

公司：微医

分类：JavaScript

[答案&解析]()

<br/>

### formData 和原生的 ajax 有什么区别

公司：宝宝树

分类：JavaScript

[答案&解析]()

<br/>

### 介绍下表单提交，和 formData 有什么关系

公司：宝宝树

分类：JavaScript

[答案&解析]()

<br/>

### promise 如何实现 then 处理，动手实现 then

公司：宝宝树

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 如何对相对路径引用进行优化

公司：宝宝树

分类：JavaScript

[答案&解析]()

<br/>

### 如何处理异常捕获

公司：海康威视

分类：JavaScript

[答案&解析]()

<br/>

### 项目如何管理模块

公司：海康威视

分类：JavaScript

[答案&解析]()

<br/>

### 尽可能多的写出判断数组的方法

公司：海康威视、新东方

分类：JavaScript

[答案&解析]()

<br/>

### 介绍 localstorage 的 api

公司：海康威视

分类：JavaScript

[答案&解析]()

<br/>

### 使用原型最大的好处

公司：蘑菇街

分类：JavaScript

[答案&解析]()

<br/>

### 单例、工厂、观察者项目中实际场景

公司：酷家乐

分类：JavaScript

[答案&解析]()

<br/>

### 添加原生事件不移除为什么会内存泄露，还有哪些地方会存在内存泄漏

公司：酷家乐

分类：JavaScript

[答案&解析]()

<br/>

### setInterval 需要注意的点

公司：酷家乐

分类：JavaScript

[答案&解析]()

<br/>

### 定时器为什么是不精确的

公司：酷家乐

分类：JavaScript

[答案&解析]()

<br/>

### setTimeout(1)和 setTimeout(2)之间的区别

公司：酷家乐

分类：JavaScript

[答案&解析]()

<br/>

### 介绍宏任务和微任务

公司：酷家乐

分类：JavaScript

[答案&解析]()

<br/>

### promise 里面和 then 里面执行有什么区别

公司：酷家乐

分类：JavaScript

[答案&解析]()

<br/>

### 介绍 class 和 ES5 的类以及区别

公司：酷家乐

分类：JavaScript

[答案&解析]()

<br/>

### 介绍 defineProperty 方法，什么时候需要用到

公司：酷家乐

分类：JavaScript

[答案&解析]()

<br/>

### for..in 和 object.keys 的区别

公司：酷家乐

分类：JavaScript

[答案&解析]()

<br/>

### 使用闭包特权函数的使用场景

公司：酷家乐

分类：JavaScript

[答案&解析]()

<br/>

### JavaScript 是什么范式语言

公司：海风教育

分类：JavaScript

[答案&解析]()

<br/>

### Promise 有没有解决异步的问题

公司：海风教育

分类：JavaScript

[答案&解析]()

<br/>

### Promise 和 setTimeout 的区别

公司：海风教育

分类：JavaScript

[答案&解析]()

<br/>

### 按照调用实例，实现下面的 Person 方法

```js
Person("Li");
// 输出： Hi! This is Li!

Person("Dan").sleep(10).eat("dinner");
// 输出：
// Hi! This is Dan!
// 等待10秒..
// Wake up after 10
// Eat dinner~

Person("Jerry").eat("dinner").eat("supper");
// 输出：
// Hi This is Jerry!
// Eat dinner~
// Eat supper~

Person("Smith").sleepFirst(5).eat("supper");
// 输出：
// 等待5秒
// Wake up after 5
// Hi This is Smith!
// Eat supper
```

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请写出正确的执行结果

```js
var yideng = {
  bar: function () {
    return this.baz;
  },
  baz: 1,
};
(function () {
  console.log(typeof arguments[0]());
})(yideng.bar);
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出正确的执行结果

```js
function test() {
  console.log("out");
}
(function () {
  if (false) {
    function test() {
      console.log("in");
    }
    test();
  }
})();
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出正确的执行结果

```js
var x = [typeof x, typeof y][1];
typeof x;
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出正确的执行结果

```js
(function (x) {
  delete x;
  return x;
})(1);
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出正确的执行结果

```js
var x = 1;
if (function f() {}) {
  x += typeof f;
}
x;
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出正确的执行结果

```js
function f() {
  return f;
}
new f() instanceof f;
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码正确执行结果，并解释原因

```js
Object.prototype.a = "a";
Function.prototype.a = "a1";
function Person() {}
var yideng = new Person();
console.log(yideng.a);
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出正确的执行结果

```js
var yideng = [0];
if (yideng) {
  console.log(yideng == true);
} else {
  console.log("yideng");
}
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出正确的执行结果

```js
function yideng() {
  return;
  {
    a: 1;
  }
}
var result = yideng();
console.log(result.a);
```

分类：JavaScript

[答案&解析]()

<br/>

### 按要求完成代码

```js
const timeout = (ms) =>
  new Promise((resolve, reject) => {
    setTimeout(() => {
      resolve();
    }, ms);
  });
const ajax1 = () =>
  timeout(2000).then(() => {
    console.log("1");
    return 1;
  });
const ajax2 = () =>
  timeout(1000).then(() => {
    console.log("2");
    return 2;
  });
const ajax3 = () =>
  timeout(2000).then(() => {
    console.log("3");
    return 3;
  });
const mergePromise = (ajaxArray) => {
  // 1,2,3 done [1,2,3] 此处写代码 请写出ES6、ES3 2中解法
};
mergePromise([ajax1, ajax2, ajax3]).then((data) => {
  console.log("done");
  console.log(data); // data 为[1,2,3]
});
// 执行结果为：1 2 3 done [1,2,3]
```

公司：阿里

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请写出正确的执行结果

```html
<script>
  //使用未定义的变量yideng
  yideng;
  console.log(1);
</script>
<script>
  console.log(2);
</script>
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出正确的执行结果

```js
var yideng = Array(3);
yideng[0] = 2;
var result = yideng.map(function (elem) {
  return "1";
});
console.log(result);
```

分类：JavaScript

[答案&解析]()

<br/>

### 请修改代码能跳出死循环

```js
while (1) {
  switch ("yideng") {
    case "yideng":
    //禁止直接写一句break
  }
}
```

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 修改代码不造成死循环

```js
while (1) {
  console.log(Math.random());
}
```

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请写出代码正确执行结果

```js
[1 < 2 < 3, 3 < 2 < 1];
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码正确执行结果

```js
2 == [[[2]]];
```

分类：JavaScript

[答案&解析]()

<br/>

### 计算以上字节每位 ✈️ 的起码点，并描述这些字节的起码点代表什么

```js
console.log("✈️".length);
// 1.计算以上字节每位✈️的起码点
// 2.描述这些字节的起码点代表什么
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码正确执行结果，并解释原因

```js
var yidenga = Function.length,
  yidengb = new Function().length;
console.log(yidenga === yidengb);
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码正确执行结果

```js
var length = 10;
function fn() {
  console.log(this.length);
}
var yideng = {
  length: 5,
  method: function (fn) {
    fn();
    arguments[0]();
  },
};
yideng.method(fn, 1);
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码正确执行结果，并解释原因

```js
var yi = new Date("2018-08-20"),
  deng = new Date(2018, 08, 20);
[yi.getDay() === deng.getDay(), yi.getMonth() === deng.getMonth()];
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码正确执行结果

```js
for (
  let i = (setTimeout(() => console.log("a->", i)), 0);
  setTimeout(() => console.log("b->", i)), i < 2;
  i++
) {
  i++;
}
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码正确执行结果，并解释原因

```js
[typeof null, null instanceof Object];
```

分类：JavaScript

[答案&解析]()

<br/>

### 请问当前 textarea 文本框展示的内容是什么？

```html
<textarea maxlength="10" id="yideng"></textarea>
<script>
  document.getElementById("yideng").value = "a".repeat(10) + "b";
</script>
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码正确执行结果

```js
function sidEffecting(ary) {
  arr[0] = arr[2];
}
function yideng(a, b, c = 3) {
  c = 10;
  sidEffecting(arguments);
  return a + b + c;
}
yideng(1, 1, 1);
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码正确执行结果

```js
yideng();
var flag = true;
if (flag) {
  function yideng() {
    console.log("yideng1");
  }
} else {
  function yideng() {
    console.log("yideng2");
  }
}
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码正确执行结果，并解释为什么

```js
var min = Math.min(),
  max = Math.max();
console.log(min < max);
```

分类：JavaScript

[答案&解析]()

<br/>

### 请手写实现一个拖拽

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请手动实现一个浅拷贝

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 介绍 instanceof 原理，并手动实现

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请实现一个 JSON.stringfy

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请实现一个 JSON.parse

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请写出代码的正确执行结果，并解释原因？

```js
console.log("hello" + (1 < 2) ? "word" : "me");
```

公司：会小二

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码的正确执行结果，并解释原因？

```js
var a = (b = 1);
(function () {
  var a = (b = 2);
})();
console.log(a, b);
```

公司：会小二

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码的正确执行结果，并解释原因？

```js
if ([] instanceof Object) {
  console.log(typeof null);
} else {
  console.log(typeof undefined);
}
```

公司：会小二

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码的正确执行结果，并解释原因？

```js
var obj = {};
obj.name = "first";
var peo = obj;
peo.name = "second";
console.log(obj.name);
```

选项：公司：会小二

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码的正确执行结果，并解释原因？

```js
function say(word) {
  let word = "hello";
  console.log(word);
}
say("hello Lili");
```

公司：会小二

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码正确执行结果，并解释原因？

```js
function fun(n, o) {
  console.log(o);
  return {
    fun: function (m) {
      return fun(m, n);
    },
  };
}
var b = fun(0).fun(1).fun(2).fun(3);
```

公司：会小二

分类：JavaScript

[答案&解析]()

<br/>

### JavaScript 中如何模拟实现方法的重载

公司：会小二

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请解释 JSONP 的工作原理

公司：会小二、安居客

分类：JavaScript

[答案&解析]()

<br/>

### 用 html、css、js 模拟实现一个下拉框，使得下拉框在各个浏览器下的样式和行为完全一致，说出你的设计方案，并且重点说明功能设计时要考虑的因素。

公司：会小二

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 实现一个打点计时器

```js
/* 
  1.从start至end,每隔100毫秒console.log一个数字，每次数字增幅为1
  2.返回的对象中需要包含一个cancel方法，用于停止定时操作
  3.第一个数字需要立即输出
*/
```

公司：会小二

分类：JavaScript、编程题

[答案&解析]()

<br/>

### JavaScript 写一个单例模式，可以具体到某一个场景

公司：会小二

分类：JavaScript、编程题

[答案&解析]()

<br/>

### JavaScript 基本数据类型都有哪些？用 typeOf 判断分别显示什么？

公司：会小二、安居客

分类：JavaScript

[答案&解析]()

<br/>

### 怎么判断引用类型数据，兼容判断原始类型数据呢？

公司：会小二

分类：JavaScript

[答案&解析]()

<br/>

### 概述异步编程模型

公司：酷狗

分类：JavaScript

[答案&解析]()

<br/>

### 在一个 ul 里有 10 个 li,实现点击对应的 li,输出对应的下标

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 分别对以下数组进行去重，1:[1,'1',2,'2',3]，2:[1,[1,2,3['1','2','3'],4],5,6]

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 简述 JavaScript 中的函数的几种调用方式

分类：JavaScript

[答案&解析]()

<br/>

### 编写一个 Person 类，并创建两个不同的 Person 对象

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 手写实现 call

公司：腾讯应用宝

分类：JavaScript

[答案&解析]()

<br/>

### 手写实现 apply

分类：JavaScript

[答案&解析]()

<br/>

### 一个 dom 必须要操作几百次，该如何解决，如何优化？

分类：JavaScript

[答案&解析]()

<br/>

### 页面埋点怎么实现

分类：JavaScript

[答案&解析]()

<br/>

### 除了 jsonp、postmessage 后端控制，怎么实现跨页面通讯

分类：JavaScript

[答案&解析]()

<br/>

### 说一下 let、const 的实现，动手实现一下

分类：JavaScript、编程题

[答案&解析]()

<br/>

### addEventListener 再 removeListener 会不会造成内存泄漏

分类：JavaScript

[答案&解析]()

<br/>

### scrollview 如何进行又能优化(例如 page=100 时，往上滚动)

分类：JavaScript

[答案&解析]()

<br/>

### 原生 JavaScript 获取 ul 中的第二个 li 里边的 p 标签的内容

分类：JavaScript

[答案&解析]()

<br/>

### 说下 offsetWith 和 clientWidth、offsetHeight 和 clientHeight 的区别，说说 offsetTop，offsetLeft，scrollWidth、scrollHeight 属性都是干啥的

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 写一个函数打乱一个数组，传入一个数组，返回一个打乱的新数组

公司：快手

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 数组截取插入 splice，push 返回值，数组的栈方法、队列方法、排序方法、操作方法、迭代方法说一下

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 判断一个变量的类型，写个方法用 Object.prototype.toString 判断传入数据的类型

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 判断一个变量的类型，写个方法用 Object.prototype.toString 判断传入数据的类型？Object.prototype.toString.call(Symbol) 返回什么？

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 对作用域和闭包的理解，解释下 let 和 const 的块级作用域

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 以下代码输出什么？

```js
setTimeout(function () {
  console.log(1);
}, 0);
new Promise(function executor(resolve) {
  console.log(2);
  for (var i = 0; i < 10000; i++) {
    i == 9999 && resolve();
  }
  console.log(3);
}).then(function () {
  console.log(4);
});
console.log(5);
```

公司：心娱

分类：JavaScript

[答案&解析]()

<br/>

### switch case，case 具体是怎么比较的，哪些情况下会走到 default

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 说下 typeof()各种类型的返回值？instanceof 呢？

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### if([] == 0), [1,2] == "1,2", if([]), [] == 0 具体是怎么对比的

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 如何加快页面渲染速度，都有哪些方式

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### genertor 的实现原理

公司：滴滴、58

分类：JavaScript

[答案&解析]()

<br/>

### 判断是否是数组的方法

公司：头条

分类：JavaScript

[答案&解析]()

<br/>

### 手写 EventEmitter 实现

公司：头条、亚美科技

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 给出的两行代码为什么这么输出

```js
var s = "laohu";
s[0] = 1;
console.log(s); //laohu
var s = "laohu";
s += 2020;
console.log(s); // laohu2020
// 上面两行为什么这么输出
```

公司：老虎

分类：JavaScript

[答案&解析]()

<br/>

### 动画性能如何检测

公司：酷狗

分类：JavaScript

[答案&解析]()

<br/>

### 平时都用到了哪些设计模式

公司：酷狗、沪江、58

分类：JavaScript

[答案&解析]()

<br/>

### 对 service worker 的理解

公司：酷狗

分类：JavaScript

[答案&解析]()

<br/>

### 单点登录实现原理

公司：CVTE

分类：JavaScript

[答案&解析]()

<br/>

### 尾递归实现

公司：CVTE

分类：JavaScript

[答案&解析]()

<br/>

### 有 1000 个 dom，需要更新其中的 100 个，如何操作才能减少 dom 的操作？

公司：爱范儿

分类：JavaScript

[答案&解析]()

<br/>

### 商城的列表页跳转到商品的详情页，详情页数据接口很慢，前端可以怎么优化用户体验？

公司：爱范儿

分类：JavaScript

[答案&解析]()

<br/>

### 多个 tab 只对应一个内容框，点击每个 tab 都会请求接口并渲染到内容框，怎么确保频繁点击 tab 但能够确保数据正常显示？

公司：爱范儿

分类：JavaScript

[答案&解析]()

<br/>

### 请实现鼠标点击页面中的任意标签，alert 该标签的名称(注意兼容性)

公司：爱范儿、道一云

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 完成一个表达式，验证用户输入是否是电子邮箱

公司：爱范儿

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 原生实现 ES5 的 Object.create()方法

公司：爱范儿

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 如何记录前端再用户浏览器上发生的错误并汇报给服务器？

公司：爱范儿

分类：JavaScript

[答案&解析]()

<br/>

### 有哪几种方式可以解决跨域问题？(描述对应的原理)

公司：爱范儿

分类：JavaScript

[答案&解析]()

<br/>

### 按要求完成题目

```js
/* 
  a)在不使用vue、react的前提下写代码解决一下问题
    一个List页面上，含有1000个条目的待办列表，现其中100项在同一时间达到了过期时间，需要在对应项的text-node里添加“已过期”文字。需要尽可能减少dom重绘次数以提升性能。
  b)尝试使用vue或react解决上述问题
*/
```

公司：爱范儿

分类：JavaScript、Vue、React、编程题

[答案&解析]()

<br/>

### 你是如何组织 JavaScript 代码的？（可以从模块、组件、模式、编程思想等方面回答）

公司：爱范儿

分类：JavaScript

[答案&解析]()

<br/>

### 填充代码实现 template 方法

```js
var str = "您好，<%=name%>。欢迎来到<%=location%>";
function template(str) {
  // your code
}
var compiled = template(srt);
// compiled的输出值为：“您好，张三。欢迎来到网易游戏”
compiled({ name: "张三", location: "网易游戏" });
```

公司：网易

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请描述下为什么页面需要做优化？并写出常用的页面优化实现方案？

公司：玄武科技

分类：JavaScript

[答案&解析]()

<br/>

### 请列出至少 5 个 JavaScript 常用的内置对象，说明用途

公司：玄武科技

分类：JavaScript

[答案&解析]()

<br/>

### 请描述下 JavaScript 中 Scope、Closure、Prototype 概念，并说明 JavaScript 封装、继承实现原理。

公司：玄武科技

分类：JavaScript

[答案&解析]()

<br/>

### 请列出目前主流的 JavaScript 模块化实现的技术有哪些？说出它们的区别？

公司：玄武科技

分类：JavaScript

[答案&解析]()

<br/>

### 请用 JavaScript 代码实现事件代理

公司：玄武科技

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 实现格式化输出，比如输入 999999999，输出 999,999,999

公司：亚美科技

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 使用 JavaScript 实现 cookie 的设置、读取、删除

公司：亚美科技

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 请编写一个 JavaScript 函数 parseQueryString,它的用途是把 URL 参数解析为一个对象，url="http://iauto360.cn/index.php?key0=0&key1=1&key2=2"

公司：亚美科技

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 如何实现 a,b 两个变量的交换

公司：高思教育

分类：JavaScript

[答案&解析]()

<br/>

### 给 JavaScript 的 String 原生对象添加一个名为 trim 的原型方法，用于截取字符串前后的空白字符

公司：高思教育

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 微任务和宏任务的区别

公司：58

分类：JavaScript

[答案&解析]()

<br/>

### 小程序里面打开页面最多多少，生命周期、常用的 api 列举几个？

公司：安居客

分类：小程序

[答案&解析]()

<br/>

### 原生 JavaScript 实现图片懒加载的思路

公司：安居客

分类：JavaScript

[答案&解析]()

<br/>

### 回调函数和任务队列的区别

公司：安居客

分类：JavaScript

[答案&解析]()

<br/>

### 写出下面代码的输出结果

```js
//counter.js
let counter = 10;
export default counter;

//index.js
import myCounter from "./counter";
myCounter += 1;
console.log(myCounter);
```

公司：快手

分类：JavaScript

[答案&解析]()

<br/>

### 有这样一个函数 A,要求在不改变原有函数 A 功能以及调用方式的情况下，使得每次调用该函数都能在控制台打印出“HelloWorld”

```js
function A() {
  console.log("调用了函数A");
}
```

公司：新东方

分类：JavaScript、编程题

[答案&解析]()

<br/>

### 在浏览器执行以下代码，写出打印结果

```js
console.log("start");
setTimeout(() => {
  console.log("children2");
  Promise.resolve().then(() => {
    console.log("children3");
  });
}, 0);
new Promise(function (resolve, reject) {
  console.log("children4");
  setTimeout(function () {
    console.log("children5");
    resolve("children6");
  }, 0);
}).then((res) => {
  console.log("children7");
  setTimeout(() => {
    console.log(res);
  }, 0);
});
```

公司：新东方

分类：JavaScript

[答案&解析]()

<br/>

### 请写出弹出值，并解释为什么？

```js
alert(a);
a();
var a = 3;
function a() {
  alert(10);
}
alert(a);
a = 6;
a();
```

分类：JavaScript

[答案&解析]()

<br/>

### 写出输出值，并解释为什么

```js
function test(m) {
  m = { v: 5 };
}
var m = { k: 30 };
test(m);
alert(m.v);
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码执⾏结果，并解释为什么

```js
function yideng() {
  console.log(1);
}
(function () {
  if (false) {
    function yideng() {
      console.log(2);
    }
  }
  console.log(typeof yideng);
  yideng();
})();
```

分类：JavaScript

[答案&解析]()

<br/>

### 请写出代码执⾏结果，并解释为什么

```js
function fn() {
  console.log(this.length);
}
var person = {
  length: 5,
  method: function (fn) {
    fn();
  },
};
person.method(fn, 1);
```

分类：JavaScript

[答案&解析]()

<br/>

### 给定⼀个⼤⼩为 n 的数组，找到其中的众数。众数是指在数组中出现次数⼤于 ⌊⌊ n/2 ⌋⌋ 的元素

分类：数据结构与算反

[答案&解析]()

<br/>

### 原生实现addClass,用多种方法

分类：JavaScript

[答案&解析]()

<br/>

### 实现一个倒计时,setInterval实现的话，如何消除时间误差

分类：JavaScript

[答案&解析]()

<br/>

### 函数中的arguments是数组吗？若不是，如何将它转化为真正的数组？

公司：头条

分类：JavaScript

[答案&解析]()

<br/>

### 请写出以下代码的打印结果

```js
if([] == false){console.log(1)};
if({} == false) {console.log(2)};
if([]){console.log(3)};
if([1] == [1]){console.log(4)};
```

公司：头条

分类：JavaScript

[答案&解析]()

<br/>

### 以最小的改动解决以下代码的错误(可以使用ES6)

```js
const obj = {
  name:"jsCoder",
  skill:["es6","react","angular"],
  say:function(){
    for(var i = 0,len = this.skill.length;i<len;i++){
      setTimeout(function(){
        console.log('No.' + i + this.name);
        console.log(this.skill[i]);
        console.log('----------------');
      },0);
      console.log(i);
    }
  }
}
obj.say();

/* 
  期望得到下面的结果
  1
  2
  3
  No.1 jsCoder
  es6
  ----------------
  No.2 jsCoder
  react
  ----------------
  No.3 jsCoder
  angular
*/
```

公司：头条

分类：JavaScript

[答案&解析]()

<br/>

### 实现Function 原型的bind方法，使得以下程序最后能输出“success”

```js
function Animal(name,color){
  this.name = name;
  this.color = color;
}
Animal.prototype.say = function(){
  return `I'm a ${this.color}${this.name}`;
}
const cat = Animal.bind(null,'cat');
const cat = new Cat('white');
if(cat.say() === "I'm white cat" && cat instanceof Cat && cat instanceof Animal){
  console.log('sunccess');
}
```

公司：头条

分类：JavaScript

[答案&解析]()

<br/>

### 文件上传如何做断点续传

公司：网易、洋葱学院

分类：JavaScript

[答案&解析]()

<br/>