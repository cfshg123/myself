### JS中typeof的类型有哪些

```javascript
    console.log(typeof undefined);  //undefined
    console.log(typeof 123);  //number
	console.log(typeof NAN); //number
    console.log(typeof '123');  //string
    console.log(typeof true); //boolean
    console.log(typeof [1,2,3]);  //object
    console.log(typeof {"id": 11}); //object
    console.log(typeof null); //object
    console.log(typeof console.log);  //function
	console.log(typeof typeof []); //string
注意：typeof 返回的任何一个结果都是字符串类型  如：'number','bpolean' 都是以字符串的形式存在的
```

### 类型转换

```javascript
[]+[] // ''
{}+{} // "[object Object][object Object]"
[]+{} // "[object Object]"
{}+[] // 0
true + true //2
1+{a:1} // "1[Onject Object]"
1+[] = '1'
NaN + NaN = NaN
NaN+1 = NaN
NaN + 1 + "NaN1"
数组重写了toString的方法 
```

### JS中有哪些内置函数

```javascript
 	Object
    Array
    Boolean
    Number
    String
    Function
    Date
    RegExp
    Error
```

### js中数组的方法

| 方法                                       | 描述                                       |
| ---------------------------------------- | ---------------------------------------- |
| [concat()](http://www.runoob.com/jsref/jsref-concat-array.html) | 连接两个或更多的数组，并返回结果。                        |
| [copyWithin()](http://www.runoob.com/jsref/jsref-copywithin.html) | 从数组的指定位置拷贝元素到数组的另一个指定位置中。 //             |
| [entries()](http://www.runoob.com/jsref/jsref-entries.html) | 返回数组的可迭代对象。                                                       // |
| [every()](http://www.runoob.com/jsref/jsref-every.html) | 检测数值元素的每个元素是否都符合条件。                      |
| [fill()](http://www.runoob.com/jsref/jsref-fill.html) | 使用一个固定值来填充数组。        //                  |
| [filter()](http://www.runoob.com/jsref/jsref-filter.html) | 检测数值元素，并返回符合条件所有元素的数组。                   |
| [find()](http://www.runoob.com/jsref/jsref-find.html) | 返回符合传入测试（函数）条件的数组元素。                     |
|                                          |                                          |
| [findIndex()](http://www.runoob.com/jsref/jsref-findindex.html) | 返回符合传入测试（函数）条件的数组元素索引。                   |
|                                          |                                          |
| [forEach()](http://www.runoob.com/jsref/jsref-foreach.html) | 数组每个元素都执行一次回调函数。                         |
| [from()](http://www.runoob.com/jsref/jsref-from.html) | 通过给定的对象中创建一个数组。//                        |
|                                          |                                          |
| [includes()](http://www.runoob.com/jsref/jsref-includes.html) | 判断一个数组是否包含一个指定的值。                        |
| [indexOf()](http://www.runoob.com/jsref/jsref-indexof-array.html) | 搜索数组中的元素，并返回它所在的位置。                      |
| [isArray()](http://www.runoob.com/jsref/jsref-isarray.html) | 判断对象是否为数组。                               |
| [join()](http://www.runoob.com/jsref/jsref-join.html) | 把数组的所有元素放入一个字符串。                         |
| [keys()](http://www.runoob.com/jsref/jsref-keys.html) | 返回数组的可迭代对象，包含原始数组的键(key)。//              |
| [lastIndexOf()](http://www.runoob.com/jsref/jsref-lastindexof-array.html) | 返回一个指定的字符串值最后出现的位置，在一个字符串中的指定位置从后向前搜索。   |
| [map()](http://www.runoob.com/jsref/jsref-map.html) | 通过指定函数处理数组的每个元素，并返回处理后的数组。               |
| [pop()](http://www.runoob.com/jsref/jsref-pop.html) | 删除数组的最后一个元素并返回删除的元素。                     |
| [push()](http://www.runoob.com/jsref/jsref-push.html) | 向数组的末尾添加一个或更多元素，并返回新的长度。                 |
|                                          |                                          |
| [reduce()](http://www.runoob.com/jsref/jsref-reduce.html) | 将数组元素计算为一个值（从左到右）。///////                |
|                                          |                                          |
| [reduceRight()](http://www.runoob.com/jsref/jsref-reduceright.html) | 将数组元素计算为一个值（从右到左）。////////               |
| [reverse()](http://www.runoob.com/jsref/jsref-reverse.html) | 反转数组的元素顺序。                               |
| [shift()](http://www.runoob.com/jsref/jsref-shift.html) | 删除并返回数组的第一个元素。                           |
| [slice()](http://www.runoob.com/jsref/jsref-slice-array.html) | 选取数组的的一部分，并返回一个新数组。                      |
| [some()](http://www.runoob.com/jsref/jsref-some.html) | 检测数组元素中是否有元素符合指定条件。                      |
| [sort()](http://www.runoob.com/jsref/jsref-sort.html) | 对数组的元素进行排序。                              |
| [splice()](http://www.runoob.com/jsref/jsref-splice.html) | 从数组中添加或删除元素。                             |
| [toString()](http://www.runoob.com/jsref/jsref-tostring-array.html) | 把数组转换为字符串，并返回结果。///////                  |
| [unshift()](http://www.runoob.com/jsref/jsref-unshift.html) | 向数组的开头添加一个或更多元素，并返回新的长度。                 |
| [valueOf()](http://www.runoob.com/jsref/jsref-valueof-array.html) | 返回数组对象的原始值。////////                      |

### js中字符串的方法

| 方法                                       | 描述                                   |
| ---------------------------------------- | ------------------------------------ |
| [charAt()](http://www.runoob.com/jsref/jsref-charat.html) | 返回在指定位置的字符。                          |
| [charCodeAt()](http://www.runoob.com/jsref/jsref-charcodeat.html) | 返回在指定的位置的字符的 Unicode 编码。             |
| [concat()](http://www.runoob.com/jsref/jsref-concat-string.html) | 连接两个或更多字符串，并返回新的字符串。                 |
| [fromCharCode()](http://www.runoob.com/jsref/jsref-fromcharcode.html) | 将 Unicode 编码转为字符。////                |
| [indexOf()](http://www.runoob.com/jsref/jsref-indexof.html) | 返回某个指定的字符串值在字符串中首次出现的位置。             |
| [lastIndexOf()](http://www.runoob.com/jsref/jsref-lastindexof.html) | 从后向前搜索字符串，并从起始位置（0）开始计算返回字符串最后出现的位置。 |
| [match()](http://www.runoob.com/jsref/jsref-match.html) | 查找找到一个或多个正则表达式的匹配。////               |
| [replace()](http://www.runoob.com/jsref/jsref-replace.html) | 在字符串中查找匹配的子串， 并替换与正则表达式匹配的子串。        |
| [search()](http://www.runoob.com/jsref/jsref-search.html) | 查找与正则表达式相匹配的值。////                   |
| [slice()](http://www.runoob.com/jsref/jsref-slice-string.html) | 提取字符串的片断，并在新的字符串中返回被提取的部分。           |
| [split()](http://www.runoob.com/jsref/jsref-split.html) | 把字符串分割为字符串数组。                        |
| [substr()](http://www.runoob.com/jsref/jsref-substr.html) | 从起始索引号提取字符串中指定数目的字符。                 |
| [substring()](http://www.runoob.com/jsref/jsref-substring.html) | 提取字符串中两个指定的索引号之间的字符。                 |
| [toLowerCase()](http://www.runoob.com/jsref/jsref-tolowercase.html) | 把字符串转换为小写。                           |
| [toUpperCase()](http://www.runoob.com/jsref/jsref-touppercase.html) | 把字符串转换为大写。                           |
| trim()                                   | 去除字符串两边的空白                           |
| [valueOf()](http://www.runoob.com/jsref/jsref-valueof-string.html) | 返回某个字符串对象的原始值。 ///////               |

### js中this指向问题

​	1、函数的调用:只要是函数的调用都是指向window也就是全局变量

```javascript
function a() {
      var b = 10
      console.log(this.b)
    }
    a() // undefinde
   // 无论在什么地方只要是 a()这样的调用 this都指向window
```

​	2、对象的调用

```javascript
var o = {
    user:"追梦子",
    fn:function(){
        console.log(this.user);  //追梦子
    }
}
o.fn();
//这里的调用是用的o对象来调用 所以this指向o 不管o里面有没有这个值 不会向上一级去找  如下：
var    user="追梦子",
var o = {
    fn:function(){
        console.log(this.user);  //undefined
    }
}
o.fn();
// 这个里面在 o里面是不寻在user的  但是在window里面存在，此时this的指向是o所以只在o里面找，找不到的话就是undefined

```

​	3、当函数存在return的时候

```javascript
function fn()  
{  
    this.user = '追梦子';  
    return {};  
}
var a = new fn;  //此时a被赋值为{}
console.log(a.user); //undefined 
// 那么再看下一个例子
function fn()  
{  
    this.user = '追梦子';  
    return 1;
}
var a = new fn;  
console.log(a.user); //追梦子
// 注意： 如果返回值是一个对象（null例外，虽然null也是对象，但是null在这里和非对象是一样的处理），那么this指向的就是那个返回的对象，如果返回值不是一个对象那么this还是指向函数的实例。
```

4、call，applay、bind 


```javascript
    window.color = 'red';
	document.color = 'yellow';
	var s1 = {color: 'blue' };
    function changeColor(){
        console.log(this.color);
    }
    changeColor.call();         // red (默认传递参数)
    changeColor.call(window);   // red
    changeColor.call(document); // yellow
    changeColor.call(this);     // red
    changeColor.call(s1);       // blue
    // this指向借用的对象
```
### js中call/apply/bind的具体用法

1、作用：call()、apply()、bind() 都是用来重定义 this 这个对象的！

2、参数 ：三者的第一个参数都是this指向的对象，如果第一个参数传的是null或者undefined的时候会指向全局 也就是window

3、区别：参数的区别 call的参数是直接放进去的 如 a.call(b,c,c,c,c) 而apply的参数为（a.call(b,[c,c,c,c])）call的第二个参数是一个队列而apply的参数是一个数组 bind返回的是一个函数要用（）来调用 其他的和call是一样的

[使用方法](https://blog.csdn.net/ganyingxie123456/article/details/70855586)

### js中的闭包

什么是闭包：闭包就是外部函数嵌套内部函数，而内部函数引用了外部函数的变量

闭包的作用：保证了变量不被污染

闭包的坏处：由于内部函数用了外部函数的变量，导致外部的函数不能被释放，会造成内存泄漏

闭包的实例：

 利用定时器实现每隔一秒输出一个数字（0-9）

1、第一个想到的办法就是下面的

```javascript
  function bibao() {
      for (i = 0; i < 10; i++) {
        setTimeout(function () {
          console.log(i)
        }, 1000)
      }
    }
    bibao()
   // 然而这个结果却是同时输出10个10
```

再看下面这个

```javascript
 function bibao() {
      for (i = 0; i < 10; i++) {
        // 此处用一个自调用函数来处理这个定时器 这里就是使用了闭包
        (function (i) {
          setTimeout(function () {
            console.log(i)
          }, 1000)
        })(i)
      }
    }
    bibao()
    // 结果为一秒后同时输出0-9 只要将定时器的时间*i就可以了 当然利用es6里面的let也可以完成此效果
```

这样用就是闭包了，如果还不是很懂的可以网上找下资料来看看

### 函数的作用域链以及预解析

### 原型与原型链

### 最后还是要多多的练习（有时间可以看看以下的题目有问题的随时找我）

1、用四种方法写出数组的去重

2、如何实现对数组中的对象对象以某一个值来排序 如

```javascript
[
  {id:1,name:'zs',score:88},
  {id:2,name:'ls',score:65},
  {id:3,name:'ww',score:74},
  {id:4,name:'xl',score:99},
]
将次数组以分数多少从大道小排列
```

3、如何实现下面这种情况

```javascript
[
  ['a1'，"a2","a3"]，
  ['hah','www','sss'],
  ['pp','cc','ff'],
  ['aaa','bbb','ccc']
]
得出结果：
[
  {a1:"hah",a2:'www',a3:'sss'},
  {a1:"pp",a2:'cc',a3:'ff'},
  {a1:"aaa",a2:'bbb',a3:'ccc'},
]
  注意如果有重复的值该怎么处理？？？
```

4、数组扁平化的处理

```javascript
var arr = [1,[2,3,[4]]]
得出结果[1,2,3,4] 
```

5、写一个方法，找出字符串 "abcabcabcabcabcabda" 中 "ab" 出现的次数和位置 （indexOf有两个参数）

6、计算字符串的长度 

```javascript
let str = 'aaaa哈哈哈123'
//一个汉字是两个位置
```

7、写一个深克隆的案例 （不得看以前的代码）

8、如何在字符串中找出数字 如下

```javascript
var str = 'aa12bb3nn4nn1'
function findNumber(){
  .........
}
 返回字符串 "12341"
```



9、移除数组 arr 中的所有值与 item 相等的元素，直接在给定的 arr 数组上进行操作，并将结果返回

10、**要求：**使用js，返回1到400所有自然数中一共出现过多少次“1”，如1到21一共出现过13次“1”

​                       。。。。。。。。。。。。。。。。。。待续





### 补充文档

[axios](https://www.kancloud.cn/yunye/axios/234845)

[element ui](http://element-cn.eleme.io/#/zh-CN)

[lib-flexible](https://www.cnblogs.com/WQLong/p/7798822.html)

[Vue源码解析](https://ustbhuangyi.github.io/vue-analysis/data-driven/mounted.html)

[es6-阮一峰](http://es6.ruanyifeng.com/?search=flat&x=0&y=0#README)

[微信小程序](https://developers.weixin.qq.com/miniprogram/dev/index.html)

[mpvue文档](http://mpvue.com/)

[wepy文档](https://tencent.github.io/wepy/)

[mint ui](https://mint-ui.github.io/#!/zh-cn)