###  变量，常量声明规则： 必须以字母，下划线，或美元符号开头并可以包含字母，数字，下划线

### javascript  数据类型
- 1. `Boolean`  布尔型  `true` `false`
- 2. `Number`  数值型  整型或者浮点型
- 3. `String`  字符串  
- 4. `null` 一个表明null值的特殊关键字，JavaScript大小写敏感，因此null Null NULL和其他变量完全不同
- 5. `undefined` 变量未定义的属性
- 6. `Symbol`  ES6中新增类型。一种数据类型，它的实例是唯一且不可改变的
### JavaScript三种声明：
- 1. `var` 声明一个变量，可选择将其初始化为一个值
- 2. `let` 声明一个块作用域的局部变量，可选择将其初始化为一个值
- 3. `const` 声明一个只读的常量

###对于函数，只有函数声明会被提升到顶部，不包括函数表达式。
### 函数表达式：  表达式定义的函数，称为匿名函数。匿名函数没有函数提升


---------------------------------------------------------------------------
#### 浏览器请求方法：HEAD,GET,POST
- HEAD的头信息包括：Accept,Accept-Language,Content-Language,Last-Event-ID,Content-Type(只限于三个值application/x-www-urlencoded,multipart/form-data,text/plain)

ajax请求时，如果存在跨域现象并且没有解决，ajax是伴随跨域的


## ajax跨域请求
ajax

















----------------------------------------------------------------------
## 捕获型 冒泡型
事件捕获 event capturing :从不确定的到确定的  
- 当鼠标点击或者触发dom事件时，浏览器会从根节点开始由外向内进行事件传播。即点击了子元素，如果父元素通过事件捕获方式注册了对应的事件，会先出发父元素绑定的事件

事件冒泡 dubbed bubbling ：从确定的到不确定的  
- 与捕获事件刚好相反，事件触发由内向外进行，直至根节点

### DOM标准事件流的触发的先后顺序： <b>先捕获后冒泡</b>

##### addEventListener(event,listener,useCapture)

##### attachEvent(event,listener)
