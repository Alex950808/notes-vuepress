# JavaScript


[[toc]]



## Flag

> Vanilla JS 就是指JavaScript

* [ECMAScript支持度检测](https://github.com/ruanyf/es-checker)
* [深入理解 TypeScript](https://jkchao.github.io/typescript-book-chinese)
* [https://github.com/requirejs](https://github.com/requirejs)
* [https://github.com/amdjs](https://github.com/amdjs)
* [https://github.com/cmdjs](https://github.com/cmdjs)
* [https://github.com/seajs](https://github.com/seajs)
* 异步编程的反应式扩展rxjs [https://github.com/ReactiveX](https://github.com/ReactiveX)

+ [https://github.com/topics/validation](https://github.com/topics/validation)
+ [https://github.com/topics/validator](https://github.com/topics/validator)

* [JS刷新当前页面的几种方法总结](http://www.iqianduan.net/blog/refresh-browser-method)
* [js keyup、keypress和keydown事件 详解](https://www.cnblogs.com/manongxiaobing/archive/2012/11/05/2755412.html)
* [js中keyup-keypress-keydown以及oninput四个事件](https://blog.csdn.net/FGstudy/article/details/101854125)
* [keydown,keypress,keyup三者之间的区别](https://blog.csdn.net/qq_26102281/article/details/83785085)



**手册**

> `HTML`网页中，浏览器通过`script`标签加载脚本的默认语言是`JavaScript`，因此`type="application/javascript"`可以省略。

* [浏览器脚本教程](https://www.w3school.com.cn/b.asp)
* [参考手册](https://www.w3school.com.cn/r.asp)
* [ECMAScript 6入门](https://github.com/ruanyf/es6tutorial)
* [ECMAscript和Javascript的区别](https://www.jianshu.com/p/10cfcb536d4a)
* [es6支持情况](https://kangax.github.io/compat-table/es6)
* [检查JavaScript文件中的ES版本](https://github.com/dollarshaveclub/es-check)
* [文档对象模型 (DOM)](https://developer.mozilla.org/zh-CN/docs/Glossary/DOM)
* [JavaScript HTML DOM](https://www.w3school.com.cn/js/js_htmldom_document.asp)



**ECMAScript6**

* [在浏览器中使用javascript module](https://www.jianshu.com/p/f7db50cf956f)

- `Uncaught SyntaxError: Cannot use import statement outside a module`

> 在报错是说无法在模块外部使用`import`语句，因为`Module`的加载实现的是`es6`语法，
> 所以在浏览器加载`html`文件时，需要在`script`标签中加入`type="module"`属性。

```html
<script type="module" src="/static/js/index.js"></script>
```

- 在module中绑定事件

```js
// ECMAScript6使用全局变量配置页面绑定事件
window.getKey = getKey;
// ECMAScript6指定元素添加事件
document.querySelector("#id").addEventListener("click", testOnclick);
```


## 第三方依赖库

* [https://github.com/topics/jquery](https://github.com/topics/jquery)
* [https://github.com/topics/jquery-plugin](https://github.com/topics/jquery-plugin)
* [https://github.com/jquery](https://github.com/jquery)
    * [https://plugins.jquery.com](https://plugins.jquery.com)
    * 添加XHR2 responseType支持的jQuery插件 [https://github.com/acigna/jquery-ajax-native](https://github.com/acigna/jquery-ajax-native)
    * [https://github.com/tonytomov/jqGrid](https://github.com/tonytomov/jqGrid)
    * [https://github.com/topics/jquery-validation](https://github.com/topics/jquery-validation)
        * [https://github.com/jquery-validation](https://github.com/jquery-validation)
            * [https://www.runoob.com/jquery/jquery-plugin-validate.html](https://www.runoob.com/jquery/jquery-plugin-validate.html)
    * [https://github.com/DataTables/DataTables](https://github.com/DataTables/DataTables)
* 日期处理类库 [https://github.com/moment/moment](https://github.com/moment/moment)
    * [http://momentjs.cn](http://momentjs.cn)
* [https://github.com/matthewhudson/current-device](https://github.com/matthewhudson/current-device)
* [Babel 是一个JavaScript转换编译器](https://babeljs.io)
    * [https://www.babeljs.cn](https://www.babeljs.cn)
* [压缩或编码解码库](https://github.com/photopea)
* [压缩](https://github.com/nodeca/pako)
* [现代化的拷贝文字](http://www.clipboardjs.cn)
* [https://github.com/Stuk/jszip](https://github.com/Stuk/jszip)
* [使浏览器支持require](https://github.com/browserify)
* [https://github.com/pixijs/pixi.js](https://github.com/pixijs/pixi.js)
* [https://github.com/zenorocha/clipboard.js](https://github.com/zenorocha/clipboard.js)
    * [http://www.clipboardjs.cn](http://www.clipboardjs.cn)
* 用于缩放图像 [https://github.com/francoischalifour/medium-zoom](https://github.com/francoischalifour/medium-zoom)
* 电子表格数据工具包 [https://github.com/SheetJS](https://github.com/SheetJS)
* 绑定按键 [https://github.com/jamiebuilds/tinykeys](https://github.com/jamiebuilds/tinykeys)
* 语法高亮 [https://github.com/PrismJS](https://github.com/PrismJS)


- [https://github.com/liriliri/licia](https://github.com/liriliri/licia)
- [https://github.com/Rob--W/cors-anywhere](https://github.com/Rob--W/cors-anywhere)
- [https://github.com/apache/incubator-echarts](https://github.com/apache/incubator-echarts)
- [neditor 基于ueditor的更现代化的富文本编辑器，支持HTTPS](https://github.com/notadd/neditor)
- [https://github.com/sentsin/layui](https://github.com/sentsin/layui)



**HTTP**

* [https://github.com/wendux/fly](https://github.com/wendux/fly)
* [https://github.com/github/fetch](https://github.com/github/fetch)
* [https://github.com/axios/axios](https://github.com/axios/axios)


**导出**

* [TableExport](https://github.com/clarketm/TableExport)
* [tableExport.jquery.plugin](https://github.com/hhurz/tableExport.jquery.plugin)
* [excellentexport](https://github.com/jmaister/excellentexport)



**WEB开发**

* [https://github.com/facebook/react](https://github.com/facebook/react)
    * [https://reactnative.cn](https://reactnative.cn)
* [https://github.com/angular/angular](https://github.com/angular/angular)
    * [https://angular.cn](https://angular.cn)
* [https://github.com/zdhxiong/mdui](https://github.com/zdhxiong/mdui)
* [https://github.com/baidu/amis](https://github.com/baidu/amis)
* [https://github.com/alienzhou/web-highlighter](https://github.com/alienzhou/web-highlighter)
* [https://github.com/josdejong/mathjs](https://github.com/josdejong/mathjs)
* 单页网站 [https://github.com/alvarotrigo/fullPage.js](https://github.com/alvarotrigo/fullPage.js)



**流程图**

+ [https://github.com/topics/diagram](https://github.com/topics/diagram)
+ [https://github.com/topics/flowchart](https://github.com/topics/flowchart)

* 3D库 [https://github.com/mrdoob/three.js](https://github.com/mrdoob/three.js)
* 图表库 [https://github.com/NorthwoodsSoftware/GoJS](https://github.com/NorthwoodsSoftware/GoJS)
* [https://github.com/jsplumb](https://github.com/jsplumb)
* [https://github.com/antvis](https://github.com/antvis)
* [https://github.com/noflo](https://github.com/noflo)
* [https://github.com/fex-team](https://github.com/fex-team)
* [https://github.com/bpmn-io](https://github.com/bpmn-io)
* [https://github.com/dagrejs](https://github.com/dagrejs)
* [https://github.com/jgrap](https://github.com/jgraph)
    * [https://github.com/jinzhanye/pokemon-diagram](https://github.com/jinzhanye/pokemon-diagram)
    * [mxGraph 入门实例教程](https://segmentfault.com/a/1190000018510996)
* [https://github.com/fabricjs](https://github.com/fabricjs)
* [https://github.com/cytoscape](https://github.com/cytoscape)
* [https://github.com/paperjs](https://github.com/paperjs)
* [https://github.com/d3](https://github.com/d3)
* [https://github.com/freegroup/draw2d](https://github.com/freegroup/draw2d)
* [https://github.com/projectstorm/react-diagrams](https://github.com/projectstorm/react-diagrams)
* [https://github.com/auto-workflow/AWorkflow](https://github.com/auto-workflow/AWorkflow)
* [https://github.com/mermaidjs/mermaid-live-editor](https://github.com/mermaidjs/mermaid-live-editor)
* 实体建模 [https://github.com/jscad](https://github.com/jscad)
    * [https://github.com/uetchy/cadmio](https://github.com/uetchy/cadmio)
    * [https://github.com/gilboonet](https://github.com/gilboonet)
* [https://github.com/adrai](https://github.com/adrai)
* [https://github.com/socketio](https://github.com/socketio)
* [https://www.jointjs.com](https://www.jointjs.com)
    * [https://resources.jointjs.com/tutorials/joint/tutorials/ports.html](https://resources.jointjs.com/tutorials/joint/tutorials/ports.html)




**Player**

* [萌豚技术组织 | 播放器、音视频、弹幕相关开源开发](https://github.com/MoePlayer)
* [Plyr–一个轻量级的HTML5播放器](https://github.com/sampotts/plyr)



**反爬虫**

* [https://github.com/antoinevastel/fpscanner](https://github.com/antoinevastel/fpscanner)
* [https://github.com/ta7sudan/secan](https://github.com/ta7sudan/secan)
* [前端如何检测Chrome-Headless不被爬虫虐](https://mlln.cn/2019/07/05/%E5%89%8D%E7%AB%AF%E5%A6%82%E4%BD%95%E6%A3%80%E6%B5%8BChrome-Headless%E4%B8%8D%E8%A2%AB%E7%88%AC%E8%99%AB%E8%99%90)


## 循环loop

- `for` 多次遍历代码块
- `forEach` 遍历对象属性，不能中断循环（使用`break`语句或使用`return`语句）
- `for/in` 遍历对象属性，实际是为循环`enumerable`对象而设计，不推荐用`for/in`来循环一个数组
- `for/of` 可遍历`Array`、`String`、`TypedArray`、`Map`、`Set`、`DOM collections`、`enumerable`、`generators`，弥补了`forEach`和`for/in`循环的短板
- `while` 当指定条件为 true 时循环一段代码块
- `do/while` 当指定条件为 true 时循环一段代码块



## 字符串换行和拼接

**字符串多行换行**

- Multiline String 多行字符串
- Template String 模板字符串
- Text Blocks 文本块

* [https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/template_strings](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/template_strings)

```js
var x = "我的\
博客\
https://www.bajins.com";
console.log(x);
```

```js
var x = "我的"+
"博客"+
"https://www.bajins.com";
console.log(x);
```

```js
var x =['我的',
    '博客',
    'https://www.bajins.com'
].join('');
console.log(x);
```

```js
var f = function () {/*
      我的博客：
      https://www.bajins.com
*/};

// 定义一个实现多行字符串的函数
Function.prototype.multiLine = function () {
    var str = this.toString().split('\n');
    return str.slice(1, str.length - 1 ).join('\n');
}

Function.prototype.getMultiLine = function() {
    var lines = this.toString();
    return lines.substring(lines.indexOf("/*") + 3, lines.lastIndexOf("*/"));  
}

console.log(f.multiLine());
console.log(f.getMultiLine());
```

- ECMAScript6语法

```js
var x = `我的
博客
https://www.bajins.com`;
console.log(x);
```


**字符串拼接**


```js
var x = "我的博客${?}";
x=x.replace("${?}","https://www.bajins.com");
console.log(x);
```

```js
var b="博客";
var x = "我的" + b + "https://www.bajins.com";
console.log(x);
```

- ECMAScript6语法

```js
var b="博客";
var x = `我的${b}https://www.bajins.com`;
console.log(x);
```




## 正则表达式

- `exec`是正则表达式的方法，参数是字符串
- `match`字符串的方法，参数是正则表达

1. 当正则表达式无子表达式，并且定义为非全局匹配时：exec和match执行的结果是一样，均返回第一个匹配的字符串内容；
2. 当正则表达式无子表达式，并且定义为全局匹配时：exec和match执行，做存在多处匹配内容，则match返回的是多个元素数组；
3. 当正则表达式有子表示时，并且定义为非全局匹配：exec和match执行的结果是一样返回多个匹配内容数组；
4. 当正则表达式有子表示时，并且定义为全局匹配：exec和match执行的结果不一样，此时match将忽略子表达式，只查找全匹配正则表达式并返回所有内容；

> 也就说，exec与全局是否定义无关系，而match则于全局相关联，当定义为非全局，两者执行结果相同；
> exec没有匹配返回null，匹配有子表达式返回匹配结果数组下标0值为所有表达式结果，其他下标为子表达式的匹配

```js
var str = `test https://www.bajins.com`; 
console.log(new RegExp("var servers = (.*)","ig").exec(str));
console.log(str.match(new RegExp("var servers = (.*)","ig")));
console.log(new RegExp("test(.*)","ig").exec(str));
console.log(str.match(new RegExp("test(.*)","ig")));
```


## Http

* [flyio](https://wendux.github.io/dist/#/doc/flyio/readme)
* [HTTP封装](https://github.com/woytu/key-gin/blob/master/static/js/utils)


### XMLHttpRequest

* [XMLHttpRequest—必知必会](https://www.jianshu.com/p/918c63045bc3)
* [XMLHttpRequest封装源码](https://github.com/yanxiaojun617/exercise/tree/master/src/20180410ajax)

- http,XMLHttpRequest,Ajax的关系

> http是浏览器和web服务器交换数据的协议,规范
>
> XMLHttpRequest是JavaScript的一个对象,是浏览器实现的一组api函数(方法),使用这些函数,浏览器再通过http协议请求和发送数据
>> XMLHttpRequest请求数据>使用js操作dom
>
> Ajax不是一种技术,是综合多种技术实现交互的模式:用html+css展示页面>使用

* [ajax和axios、fetch的区别](https://www.jianshu.com/p/8bc48f8fde75)
* [Fetch API](https://developer.mozilla.org/zh-CN/docs/Web/API/Fetch_API)

> fetch号称是AJAX的替代品，是在ES6出现的，使用了ES6中的promise对象。Fetch是基于promise设计的。
> Fetch的代码结构比起ajax简单多了，参数有点像jQuery ajax。
> fetch不是ajax的进一步封装，而是原生js，没有使用XMLHttpRequest对象。



## 类型判断

### typeof

> `[]`和`null`被`typeof`解释为`object`类型

> 数字`Number`，布尔值`Boolean`，字符串`String`，函数`Function`，对象`Object`，
> `Undefined`这一些数据类型在`typeof`下都被精准的解释，只有数组和`null`的数据类型不够精准。


```js
console.log(typeof 2);              // number
console.log(typeof true);           // boolean
console.log(typeof 'str');          // string
console.log(typeof []);             // object
console.log(typeof function(){});   // function
console.log(typeof {});             // object
console.log(typeof (new Date));     // object
console.log(typeof undefined);      // undefined
console.log(typeof null);           // object
```

### instanceof

> 直接的字面量值判断数据类型，只有引用数据类型`Array`、`Function`、`Object`被精准判断
>
> 数值`Number`，布尔值`Boolean`，字符串`String`等字面值不能被`instanceof`精准判断。

> 在MDN中的解释：`instanceof`运算符用来测试一个对象在其原型链中是否存在一个构造函数的`prototype`属性。

```js
console.log(2 instanceof Number);               // false
console.log(true instanceof Boolean);           // false
console.log('str' instanceof String);           // false
console.log([] instanceof Array);               // true
console.log(function(){} instanceof Function);  // true
console.log({} instanceof Object);              // true
console.log(new Date() instanceof Object);      // true
console.log(undefined instanceof Undefined);    // 报错
console.log(null instanceof Null);              // 报错
```


### constructor

> 如果创建一个对象，更改它的原型，这种方式也变得不可靠了。

```js
console.log((2).constructor == Number);                 // true
console.log((true).constructor == Boolean);             // true
console.log(('str').constructor == String);             // true
console.log(([]).constructor == Array);                 // true
console.log((function() {}).constructor == Function);   // true
console.log(({}).constructor == Object);                // true
console.log((new Date()).constructor == Date);          // true
console.log((undefined).constructor == Undefined);      // 报错
console.log((null).constructor == Null);                // 报错
```


### call

> `Object.prototype.toString.call()`即使改变对象的原型，依然会显示正确的数据类型

```js
var a = Object.prototype.toString;
console.log(a.call(2));             // [object Number]
console.log(a.call(true));          // [object Boolean]
console.log(a.call('str'));         // [object String]
console.log(a.call([]));            // [object Array]
console.log(a.call(function(){}));  // [object Function]
console.log(a.call({}));            // [object Object]
console.log(a.call(new Date()));    // [object Date]
console.log(a.call(undefined));     // [object Undefined]
console.log(a.call(null));          // [object Null]
```


## errors

> `ECMAScript`定义了六种类型的错误。还可以使用`throw new Error("错误信息")`抛出自定义异常。

1. `ReferenceError` 找不到对象时
2. `TypeError` 错误的使用了类型或对象的方法时
3. `RangeError` 使用内置对象的方法时，参数超范围
4. `SyntaxError` 语法写错了
5. `EvalError` 错误的使用了Eval
6. `URIError` URI错误

```js
try{
    // 可能发生错误的代码
}catch(err){
    // 只有发生错误时才执行的代码
}finally{
    // 无论是否出错，肯定都要执行的代码
}
```

```js
class CustomError extends Error {
  constructor(message) {
    super(message);
    this.name = this.constructor.name;
    Error.captureStackTrace(this, this.constructor);
  }
}

class TimeoutError extends CustomError {}

module.exports = {
  TimeoutError,
};
```

## 定时延时

```js
//6000毫秒后执行testFunction()函数，只执行一次。
setTimeout(function (){
    // 业务逻辑

}, 6000);

//每隔6000毫秒执行一次testFunction()函数，执行无数次。
var interval = window.setInterval(function (){
    // 业务逻辑

}, 6000);
// 停止执行setInterval循环。
window.clearInterval(interval);

setInterval(function(){
    // 业务逻辑

}, 6000);
```

```js
//第一种，使用while循环
function sleep(delay) {
    var start = (new Date()).getTime();
    while((new Date()).getTime() - start < delay) {
        continue;
    }
}
//或者使用for循环
function sleep(delay) {
    for(var t = Date.now(); Date.now() - t <= delay;);
}
```




## blob转json


```js
// 如果服务器错误返回
if (result.data.type === 'application/json') {
    let reader = new FileReader();
    reader.readAsText(result.data, 'utf-8');
    reader.onload = (e) => {
        console.log(JSON.parse(reader.result));
        console.log(JSON.parse(e.target.result));
    }
    reader.onload = function (e) {
        console.log(JSON.parse(reader.result));
        console.log(JSON.parse(e.target.result));
    }
}
```



## 获取元素

```js
document.getElementById('元素的ID')
document.getElementsByTagName('元素的标签名')
// 通过元素的name属性的值获取一组元素
context.getElementsByName()
// 通过元素的类名（class的值）
context.getElementsByClassName()
// 获取HTML元素
document.documentElement
// 获取body元素
document.body
// 获取一个(IE6~8下不兼容)
document.querySelector()
// 获取多个(IE6~8下不兼容)
document.querySelectorAll()
```



## 获取宽高

```js
// 屏幕可用工作区宽度
screen.availWidth
// 屏幕可用工作区高度
screen.availHeight

// 屏幕分辨率的宽
screen.width
// 屏幕分辨率的高
screen.height

// 网页正文部分上
window.screenTop
// 网页正文部分左
window.screenLeft

// 设置或获取位于给定对象左边界与窗口中目前可见内容的最左端之间的距离
window.scrollLeft
// 设置或获取位于给定对象最顶端与窗口中目前可见内容的最顶端之间的距离
window.scrollTop

// 设置或获取位于给定对象相对于版面或由offsetParent属性指定的父坐标的计算左侧位置
window.offsetLeft
// 设置或获取位于给定对象相对于版面或由offsetParent属性指定的父坐标的计算顶端位置
window.offsetTop

// 浏览器窗口的内部宽高，会随窗口的显示大小改变
window.innerWidth
window.innerHeight

// 网页可见区域宽度，不包括工具栏和滚动条，会随窗口的显示大小改变
document.body.clientWidth
document.documentElement.clientWidth
// 网页可见区域高度，不包括工具栏和滚动条，会随窗口的显示大小改变
document.body.clientHeight
document.documentElement.clientHeight

// 网页可见区域宽度，包括滚动条等边线，会随窗口的显示大小改变
document.body.offsetWidth
document.documentElement.offsetWidth
// 网页可见区域高度，包括滚动条等边线，会随窗口的显示大小改变
document.body.offsetHeight
document.documentElement.offsetHeight

// 网页正文全文宽度(不包括滚动条)，会随窗口的显示大小改变
document.body.scrollWidth
document.documentElement.scrollWidth
// 网页正文全文宽度(不包括滚动条)，会随窗口的显示大小改变
document.body.scrollHeight
document.documentElement.scrollHeight
```


## 标签默认动作


```js
function test(event){
    // 阻止事件冒泡
    event.stopPropagation();
    // 和event.stopPropagation()效果相同 ，根据浏览器兼容性判断使用哪种方法
    event.cancelBubble();
}
```

- href伪协议

```html
<a href="javascript:void(0);" onclick="test()">{{ row.name }}</a>
```


- 原生方式

* [event.preventDefault](https://developer.mozilla.org/zh-CN/docs/Web/API/Event/preventDefault)

```html
<a href="https://www.bajins.com" onclick="test();return false;">{{ row.name }}</a>
```


```html
<a href="https://www.bajins.com" onclick="return test();">{{ row.name }}</a>
<script>
function test(){
    return false;
}
</script>
```


```html
<a href="https://www.bajins.com" onclick="test();return false;">{{ row.name }}</a>
<script>
function test(event){
    event = event || window.event;
    window.event? window.event.returnValue = false : event.preventDefault();
}
</script>
```


- VUE阻止默认行为

* [事件修饰符](https://cn.vuejs.org/v2/guide/events.html#%E4%BA%8B%E4%BB%B6%E4%BF%AE%E9%A5%B0%E7%AC%A6)
* [v-on api](https://cn.vuejs.org/v2/api/#v-on)

```html
<a href="https://www.bajins.com" v-on:click.prevent="test()">{{ row.name }}</a>
```

```html
<a href="https://www.bajins.com" v-on:click="test($event)">{{ row.name }}</a>
<script>
    function test(event){
        event.preventDefault();
    }
</script>
```


## 封包闭包

```js
(function () {
    // 全局对象
    window.utils = {};
}());
```

```js
(function (w) {
    // 全局对象
    var utils = function () {

    };
    // 兼容AMD,CMD和原生JS
    if (typeof define === "function" && (define.amd || define.cmd)) {
        define(function () {
            return new utils();
        });
    } else {
        w.utils = new utils();
    }
})(window);
```

```js
; (function () {
    var utils = function () {
        // ... 
    }
    // 兼容AMD,CMD和原生JS
    if (typeof module !== 'undefined' && typeof exports === 'object' && define.cmd) {
        module.exports = utils;
    } else if (typeof define === 'function' && define.amd) {

        define(function () { return utils; });

    } else {
        this.utils = utils;
    }
}).call(function () {
    return this || (typeof window !== 'undefined' ? window : global);
});
```

```js
$(function (w) {
    // 全局对象
    window.utils = {};
}($));
```

```js
(function ($) {
    // 全局对象
    window.utils = {};
})(jQuery);
```

```js
$(function () {
    // 全局对象
    window.utils = {};
});
```

```js
jQuery(function ($) {
    // 全局对象
    window.utils = {};
});
```

```js
$(document).ready(function () {
    // 全局对象
    window.utils = {};
})
```


## Storage和Cache

* [使用Chrome DevTools查看和编辑本地存储](https://developers.google.com/web/tools/chrome-devtools/storage/localstorage)
* [Web Storage API](https://developer.mozilla.org/zh-CN/docs/Web/API/Web_Storage_API)

> storage存储的数据只能是字符串类型，其他类型的数据需做类型转换

**Cookie和Storage的区别**

1. cookie兼容所有的浏览器（本地cookie谷歌不支持），storage不支持IE6~8;
2. 二者对存储的内容均有大小限制，前者同源情况写一般不能存储4kb的内容，后者同源一般能存储只能存储5MB的数据
3. cookie有过期时间，localStorage是永久存储（如果你不手动去删除的话）
4. 一些浏览器处于安全的角度可能会禁用cookie,但无法禁用localStorage



**Session Storage**

```js
sessionStorage.setItem("key", "value");
var value = sessionStorage.getItem("key");
sessionStorage.removeItem("key");
sessionStorage.clear();

var storage = window.sessionStorage;
for(var i=0, len=storage.length; i<len;i++){
    var key = storage.key(i);    
    var value = storage.getItem(key);    
    console.log(key + "=" + value);
}
```

**Local Storage**

```js
localStorage.getItem('mobile');
var value = localStorage.setItem('mobile',"要存的数据");
```


**IndexedDB**

* [IndexedDB_API](https://developer.mozilla.org/zh-CN/docs/Web/API/IndexedDB_API)
* [使用IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API/Using_IndexedDB)

**Web SQL**

> 该规范不再处于主动维护中，并且Web应用程序工作组不打算进一步维护它。

* [https://www.w3.org/TR/webdatabase](https://www.w3.org/TR/webdatabase)

**Cahce Storage**

* [https://developer.mozilla.org/zh-CN/docs/Web/API/Cache](https://developer.mozilla.org/zh-CN/docs/Web/API/Cache)


**Application Cache**

* [HTML5 - 应用程序缓存(Application Cache)](https://blog.csdn.net/weixin_44198965/article/details/89760924)

**jQuery数据缓存方案**

> 使用隐藏控件或者js全局变量来临时存储数据，全局变量容易导致命名污染，隐藏控件导致经常读写dom浪费性能。jQuery提供了数据缓存方案

- `$.data()`
- `$.cache`
- `$.expando`
- `$.hasData()`
- `$.removeData()`

```js

var myObj = {};
// hasData用来判断HTMLElement或JS对象是否具有数据
console.log(jQuery.hasData($("#a")));// false
 
// data()添加属性
$.data(myObj, 'name', 'aty');
console.log(jQuery.hasData(myObj));// true
 
// data()读取属性
console.log($.data(myObj, 'name'));//aty
 
// removeData删除属性
$.removeData(myObj, 'name');
console.log($.data(myObj, 'name'));//undefined
 
// 如果所有属性都被删除,那么hasData返回false
console.log(jQuery.hasData(myObj));// false
```