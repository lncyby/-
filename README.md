### 1.请尽可能多的列出隐藏一个元素的 css 方法
```
.hide {   
    display:none;   
}  
.hidden{   
    visibility:hidden  
} 
.hiddenBox {   
    margin:0;   
    border:0;   
    padding:0;   
    height:0;   
    width:0;   
    overflow:hidden;   
}  
.none { display: none; }   
    .hidden { visibility: hidden; }   
    .opacity0 { opacity: 0; }   
    .height0 { height: 0; }  
```
### 2.水平垂直居中一个元素的方法有那些？
```
#a{
 4    height:300px;
 5   width:300px;
 6   position:absolute;
 7   top:50%;
 8   left:50%;
 9   margin-left:-150px;
10   margin-top:-150px;
11 }
#a{ 
    width: 50%;
    height: 20%;
    background: green;
    position: absolute;
    top:50%;
    left: 50%;
    transform:translate(-50%, -50%);
        -webkit-transform:translate(-50%, -50%);
        -ms-transform:translate(-50%, -50%);
}
#a{  
    width: 200px;
    height: 200px;
    background: red;
    margin:auto;
    position: absolute;
    top:0;left:0;right: 0;bottom: 0;
}
```
### 3.css 的定位有那些样式，请分别列出，并写出他们之间的区别
```
CSS的Position很重要，有以下几个值：static，relative，absolute，fixed。
Static：静态定位。如果你没有设置position属性，那么缺省就是static。top，left，bottom，right等属性，在static的情况下是无效的，要使用这些属性，必须把position设置为其他三个值之一。
position:fixed; 相对于浏览器窗口绝对定位。
_position:absolute; 只有IE6能识别, IE6不支持fixed, 所以针对IE6使用absolute绝对定位, 一般还要配套一个expression脚本来实现。
```
### 4.css3 新增的属性常用的有哪些，请分别列举
```
box-shadow(阴影效果)
border-colors(为边框设置多种颜色)
boder-image(图片边框)
ext-overflow(文本截断)
word-wrap(自动换行)
border-radius(圆角边框)
opacity(不透明度)   
box-sizing(控制盒模型的组成模式)
```
### 5.html5 新增的特性有哪些，分别列举
```
新的文档类型  (New Doctype) <!DOCTYPE html>。
脚本和链接无需type
更加语义化的元素
占位符 (Placeholder)
Audio 和Video 支持
HTML5 canvas
```
### 6.你有那些性能优化的方法
```
第一：面向内容的优化
1. 减少 HTTP 请求 
2. 减少 DNS 查找
3. 避免重定向
4. 使用 Ajax 缓存
5. 延迟载入组件
6. 预先载入组件 
7. 减少 DOM 元素数量
8. 切分组件到多个域
9. 最小化 iframe 的数量
10.  不要出现http 404 错误
第二：面向 Server
1. 缩小 Cookie 
2. 针对 Web 组件使用域名无关性的
```
### 7.数组方法 pop() push() unshift() shift() 分别是什么意思
```
shift:从集合中把第一个元素删除，并返回这个元素的值。
unshift: 在集合开头添加一个或更多元素，并返回新的长度
push:在集合中添加元素，并返回新的长度
pop:从集合中把最后一个元素删除，并返回这个元素的值。
```
### 8.jQuery 绑定 click 的方法有几种
```
$('li').click(function(){
    console.log(this)
});
$(document).on('click', 'li', function(){
    console.log(this)
})

```

### 9.请用 div+css 写出左侧固定(width:300)，右侧固定(width:300)，中间自动适应页面布局
```
<div style="width:1000px; border:#0000FF solid 1px; margin:0 auto">
    <div style="float:right; width:300px; border:#000 solid 2px;">宽度为300像素</div>
    <div style="float:left; width:auto; border:#FF0000 solid 2px;">宽度为自动适应0000000000000000000000000</div>
    <div style="float:right; width:300px; border:#000 solid 2px;">宽度为300像素</div>
```
### 10.定义一个方法，用来获取 url 后面的参数并改变为对象
```

```


### Demo++面试：

### 1. Django 启动服务器
  python manage.py runserver
### 2. Django 数据库同步命令
  manage.py syncdb
### 3. react原理
  React中的组件并不是真实的DOM节点, 而是存在于内存之中的一种数据结构,   
  叫做虚拟DOM(virtual DOM). 只是当它插入文档以后, 才会变成真实的DOM.   
  根据React的设计, 所有的DOM变动, 都先丰虚拟DOM上发生, 然后再将实际  
  发生变动的部分, 反映在真实DOM上, 这种算法叫做DOM diff, 这样可以大大  
  提高网页的性能表现.
### 4. gitflow开发流程  
  Gitflow工作流定义了一个围绕项目发布的严格分支模型。虽然比功能分支工  
  作流复杂几分，但提供了用于一个健壮的用于管理大型项目的框架。
  
### 5. es6字符串模板的使用

ES6引入了一种新型的字符串字面量语法，我们称之为模板字符串（template strings）。  
除了使用反撇号字符 ` 代替普通字符串的引号 ' 或 " 外，它们看起来与普通字符串并无二致

### 6. react中子组件怎样向父组件传递信息
父向子孙传值用props；子孙向父传值，要在父设置接收函数和state，同时用props将函数名传入子孙


### 软通面试

#### 软通面试一：

### 1. div中如何让一个子元素一直处于该div的右上角
   定位
### 2. BootStrap中网吧布局，怎样将页面水平方向布置成四块
  col-md-4
  col-md-4
  col-md-4
  col-md-4
### 3. BootStrap 如何让内容居中
  container
### 4. BootStrap 新添加样式的方式
   !important
### 5. 对象a中有两个方法b和c，怎样在对象内部中b调用c
```
B={this.C=[[a,b,c],[1,2,3],...];
this.D=int;}
var A={this.B=B;
this.方法=?;}

```
### 6. React是不是数据双向绑定
不是
### 7. 说说同步和异步的区别
```
同步：当一个调用发出时，调用不会立即返回直到得到调用结果
异步：当一个调用发出时，调用着线程不需要等待调用结果的返回就可以继续执行后续操作
```
### 8. 举例说明什么情况下需要使用同步方式



#### 软通面试二：

### 1. css文件的引用方式，有什么区别
内部引用，在html文档中在<style>标签里面写的css样式
外部引用，用<link>标签引用外部的css文件，将样式引用到html文档来。
在标签中使用，使用style属性将当前的标签样式改变。

### 2. js 中 splite 和join的区别
join()方法用于把数组中的所有元素放入1个字符串。
split()方法：用于把1个字符串分割成字符串数组

### 3. get方法和post方法的泣别
get是从服务器上获取数据，post是向服务器传送数据。

### 4. ajax中的load怎么使用
```
$(selector).load(URL,data,callback);
```

### 1. tcp与udp的区别。tcp是怎么保证数据的安全。
```
1.基于连接与无连接；
2.对系统资源的要求（TCP较多，UDP少）；
3.UDP程序结构较简单；
4.流模式与数据报模式 ；
5.TCP保证数据正确性，UDP可能丢包，TCP保证数据顺序，UDP不保证。
```
### 3. 三次握手、七层模型和四层模型。
   1、主机到网络层　　
　　实际上TCP/IP参考模型没有真正描述这一层的实现，只是要求能够提供给其上层-网络互连层一个访问接口，以便在其上传递IP分组。由于这一层次未被定义，所以其具体的实现方法将随着网络类型的不同而不同。　　
　　2、网络互连层　　
　　网络互连层是整个TCP/IP协议栈的核心。它的功能是把分组发往目标网络或主机。同时，为了尽快地发送分组，可能需要沿不同的路径同时进行分组传递。因此，分组到达的顺序和发送的顺序可能不同，这就需要上层必须对分组进行排序。　　
　　网络互连层定义了分组格式和协议，即IP协议（Internet Protocol）。　　
　　网络互连层除了需要完成路由的功能外，也可以完成将不同类型的网络（异构网）互连的任务。除此之外，网络互连层还需要完成拥塞控制的功能。　　
　　3、传输层　　
　　在TCP/IP模型中，传输层的功能是使源端主机和目标端主机上的对等实体可以进行会话。在传输层定义了两种服务质量不同的协议。即：传输控制协议TCP（transmission control protocol）和用户数据报协议UDP（user datagram protocol）。　　
　　TCP协议是一个面向连接的、可靠的协议。它将一台主机发出的字节流无差错地发往互联网上的其他主机。在发送端，它负责把上层传送下来的字节流分成报文段并传递给下层。在接收端，它负责把收到的报文进行重组后递交给上层。TCP协议还要处理端到端的流量控制，以避免缓慢接收的接收方没有足够的缓冲区接收发送方发送的大量数据。　　
　　UDP协议是一个不可靠的、无连接协议，主要适用于不需要对报文进行排序和流量控制的场合。　　
　　4、应用层　　
　　TCP/IP模型将OSI参考模型中的会话层和表示层的功能合并到应用层实现。　　
　　应用层面向不同的网络应用引入了不同的应用层协议。其中，有基于TCP协议的，如文件传输协议（File Transfer Protocol，FTP）、虚拟终端协议（TELNET）、超文本链接协议（Hyper Text Transfer Protocol，HTTP），也有基于UDP协议的。

### 2. django中的中间件是干嘛用的？怎么创建中间件
  
### 3. python中的封装继承和多态
```
多态： 可对不同类的对象使用同样的操作。
封装：对外部世界隐藏对象的工作细节。 
继承：以普通的类为基础建立专门的类对象。
```
### 4. 进程间的通信方式
```
# 管道( pipe )：管道是一种半双工的通信方式，数据只能单向流动，而且只能在具有亲缘关系的进程间使用。进程的亲缘关系通常是指父子进程关系。
# 有名管道 (named pipe) ： 有名管道也是半双工的通信方式，但是它允许无亲缘关系进程间的通信。
# 信号量( semophore ) ： 信号量是一个计数器，可以用来控制多个进程对共享资源的访问。它常作为一种锁机制，防止某进程正在访问共享资源时，其他进程也访问该资源。因此，主要作为进程间以及同一进程内不同线程之间的同步手段。
# 消息队列( message queue ) ： 消息队列是由消息的链表，存放在内核中并由消息队列标识符标识。消息队列克服了信号传递信息少、管道只能承载无格式字节流以及缓冲区大小受限等缺点。
# 信号 ( sinal ) ： 信号是一种比较复杂的通信方式，用于通知接收进程某个事件已经发生。
# 共享内存( shared memory ) ：共享内存就是映射一段能被其他进程所访问的内存，这段共享内存由一个进程创建，但多个进程都可以访问。共享内存是最快的 IPC 方式，它是针对其他进程间通信方式运行效率低而专门设计的。它往往与其他通信机制，如信号两，配合使用，来实现进程间的同步和通信。
# 套接字( socket ) ： 套解口也是一种进程间通信机制，与其他通信机制不同的是，它可用于不同及其间的进程通信。
```
### 5. 在shell下怎么配置环境变量

### 6. python中怎么出去list中重复的元素
```
来自比较容易记忆的是用内置的set

l1 = ['b','c','d','b','c','a','a'] 
l2 = list(set(l1)) 
print l2
```
### 7. 有没有改过mysql配置文件，SQL注入，mysql的运行时间
```

```
### 8. 怎么使用git在网上拉一个分支到本地开发？
```
git checkout -b 本地分支名x origin/远程分支名x
```

### 1. 说说rem、px、em的区别
```
PX:
PX实际上就是像素，用PX设置字体大小时，比较稳定和精确。但是这种方法存在一个问题，当用户在浏览器中浏览我们制作的Web页面时，如果改变了浏览器的缩放，这时会使用我们的Web页面布局被打破。这样对于那些关心自己网站可用性的用户来说，就是一个大问题了。因此，这时就提出了使用“em”来定义Web页面的字体。
EM:
EM就是根据基准来缩放字体的大小。EM实质是一个相对值，而非具体的数值。这种技术需要一个参考点，一般都是以<body>的“font-size”为基准。如WordPress官方主题Twenntytwelve的基准就是14px=1em。
另外，em是相对于父元素的属性而计算的，如果想计算px和em之间的换算，输入数据就可以px和em相互计算。
Rem:
EM是相对于其父元素来设置字体大小的，这样就会存在一个问题，进行任何元素设置，都有可能需要知道他父元素的大小。而Rem是相对于根元素<html>，这样就意味着，我们只需要在根元素确定一个参考值。

```
### 2. 有没有看过jquery源码？ 说说？
### 3. 前端性能优化？你怎么看待兼容性这块？说说你的理解？
```
1.html、css、js三者相分离。分离得彻底点！为什么这三者要分离，相信大家都明白，不多说。 
2.css的导入方式。css用link而不用@import，因为在 IE 中 @import 指令等同于把 link 标记写在 HTML 的底部，延长css的载入时间，还可能出现文件下载次序被更改的情况。 
3.理性对待jquery。jquery让我们“write less,do more”，它有太多优势：强大的选择器、DOM操作的完美封装、完善的Ajax、良好的兼容性处理。但是，我们是否就此离不开它呢？我觉得应该根据需求，根据业务逻辑来。一个页面如果只需要几行或几十行js代码可以搞定的效果，为什么要用jquery？让页面先加载个jquery.js，再书写自己的代码？没必要吧。 
4.合理布局页面的内容。DOM的加载顺序是由上而下的，遇到css，加载css，遇到js，停滞下来，加载并解析js。在布局页面的时候，把主体内容优先显示，把重要内容靠上布局，让浏览器优先解析，是种较好的方案。　 
5.js的导入方式。《javascript王者归来》里有对js的导入方式进行优劣对比。我个人认为，在不考虑js代码重用及维护的前提下(但是往往这点成为我最重要的衡量指标)，把具有重要业务模块的js代码置于title里，把次要的具有操作效果的js代码置于DOM相对应的对象之后。而这样做的理论依据即DOM的加载顺序
```
### 4. 如果简历有写移动端开发的话，会问适配的问题。遇见那种不适配的情况是怎么解决的？
### 5. 怎么理解错误优先回调函数

### 6. 你常用的node组件体系，说说为什么
```
mysql
功能简介：mysql- node.js平台mysql驱动，支持事务、连接池、集群、sql注入检测、多做参数传递写法等特性。
主页地址：https://github.com/felixge/node-mysql

eventproxy

功能简介：eventproxy- node.js 异步回调代理。主要用来解决node中深层次回调嵌套的问题，支持很多异步模式：多类型异步、重复异步、持续型异步。
主页地址：https://github.com/JacksonTian/eventproxy

validator

功能简介：javascript的验证工具集，支持两种模式：check(校验)/sanitize(处理)，同时提供了可扩展的错误处理。
主页地址：http://github.com/chriso/node-validator

ejs

 功能简介：embered.jsjavascript 模板引擎（可以跟express集成，作为服务端模板引擎）

主页地址：https://github.com/visionmedia/ejs

loader

功能简介：loader- 资源加载工具，可以区分开发模式、发布模式；在发布模式下可进行资源压缩、合并。以实现减少静态资源带宽并且便于实现客户端缓存
主页地址：https://github.com/TBEDP/loader

canvas

 

功能简介：canvas - node.js 常用的图形图像处理库，是很多其它库的基础依赖库
主页地址：https://github.com/learnboost/node-canvas

captchagen

功能简介：captchagen-node.js常用验证码图片处理库，依赖上面的canvas库
主页地址：http://github.com/wearefractal/captchagen

crypto-js

功能简介：crypto-js- javascript 常用加密库、hash库封装，支持sha-x / md5 / hash等各种加密、hash算法
主页地址：http://github.com/wearefractal/captchagen

nodemailer

功能简介：nodemailer- 邮件发送工具，支持SMTP等邮件发送协议
主页地址：http://github.com/andris9/nodemailer

qrcode

功能简介：qrcode- node.js服务端的qrcode生成器。支持多种输出类型（dataUrl/file/bitArray）
主页地址：http://github.com/soldair/node-qrcode

pdfkit

功能简介：qrcode- node.js服务端的qrcode生成器。支持多种输出类型（dataUrl/file/bitArray）
主页地址：http://github.com/soldair/node-qrcode

excel

功能简介：excel- node.js excel解析器，支持xlsx(Excel2007+)
主页地址：https://github.com/trevordixon/excel

excel-export 

功能简介：excel-export- node.js excel生成器，支持导出excel
主页地址：https://github.com/functionscope/Node-Excel-Export

net-ping

功能简介：net-ping- node.js 对ping的封装，用于测试目标主机是否可达
主页地址：https://bitbucket.org/stephenwvickers/node-net-ping

debug

功能简介：debug- node.js debug工具，对console.log的封装，支持多种颜色输出。
主页地址：https://github.com/visionmedia/debug
```

### 7. 如何用node实现一个redis ression中间件

### 8. 你怎样理解node中的面向对象

### 9. 你对node的整体理解
```
单线程

像java、PHP等这样的后端语言，都是多线程的，即当有一个请求过来的时候，开启一个CPU，它使计算机能够在同一时间执行多个线程。而node的单线程是指当遇到需要加载数据库、读取磁盘等请求的时候，它会将其放入“队列”中执行，待下一轮事件循环的时候再判断能否执行它的回调函数，若此时它的回调函数需要加载I/O则放入“队列”中，它的特点是线程利用率是100%。

事件驱动

举一个通俗点的例子，你在餐厅吃饭，如果当时店内生意比较好，你坐下来，服务员过来招待你，这时，另一桌也刚坐下并呼叫服务员。正常情况下，服务员肯定会想给你个菜单让你自己看看，看好了再叫他，接着去招呼那一桌的客人了，完了再给你端茶什么的。

这就是事件驱动。通过监听事件的状态变化来做出相应的操作。当你发出一个请求的时候，如果这个请求需要等待，那这个请求便会被放入“队列”中，在处理这个请求的同时，后续的无需请求也在被处理，事件处理结束后，调用请求的回调函数。注：在处理无需等待的事件时，事件循环是暂停的。

非阻塞I/O

阻塞I/O就是当用户发一个读取文件描述符的操作的时候，进程就会被阻塞，直到要读取的数据全部准备好返回给用户。那非阻塞I/O呢，就与上面的情况相反，用户发起一个读取文件描述符操作的时，函数立即返回，不作任何等待，进程继续执行。但是程序如何知道要读取的数据已经准备好了呢？最简单的方法就是轮询，即事件循环。


```

### 10. jquery有几种绑定事件的方法，分别是什么？
```
  bind()-------------------------版本号小于3.0（在Jquery3.0中已经移除，相应unbind()也移除）
  live()--------------------------版本号小于1.7（在Jquery1.7中已经移除，相应die()也移除）
  delegate()-------------------版本号小于1.7（在Jquery1.7中已经移除）
  on()---------------------------版本号大于1.7（在Jquery1.7中添加，相应off()也添加）

```
### 11. nextTick、setTimeout、setInterval、setImmediate的区别
```
setInterval 不断地执行指定代码直到调用clearInterval清除定时器对象
setTimeout 执行一次指定代码，使用clearTimeout清除定时器对象
```
### 12 js的面向对象
```
 面向对象的语言有一个标志，即拥有类的概念，抽象实例对象的公共属性与方法，基于类可以创建任意多个实例对象，  
 一般具有封装、继承、多态的特性！但JS中对象与纯面向对象语言中的对象是不同的，ECMA标准定义JS中对象：无序  
 属性的集合，其属性可以包含基本值、对象或者函数。可以简单理解为JS的对象是一组无序的值，其中的属性或方法都  
 有一个名字，根据这个名字可以访问相映射的值（值可以是基本值/对象/方法）
```
### 13 正则这块。
### 14 js数组和字符串都有哪些方法
```

```


/*python 面试题*/
### 以下代码的输出将是什么？
def extendList(val,list=[]):
	list.append(val)
	return list

list1 = extendList(10)
list2 = extendList(123,[])
list3 = extendList('a')

print "list1 = %s" % list1
print "list2 = %s" % list2
print "list3 = %s" % list3

### 以下的代码的输出将是什么？
def multipliers():
	return [lambda x : i * x for i in range(4)]
print [m(2) for m in multipliers()]

### 以下代码的输出将是什么?
list = ['a','b','c','d','e']
print list[10:]

### 以下代码的输出将是什么?
def div1(x,y):
	print ("%s/%s = %s" % (x,y,x/y))

def div2(x,y):
	print ("%s//%s = %s" % (x,y,x//y))

div1(5,2)
div1(5.,2)
div2(5,2)
div2(5.,2.)

### 以下代码的输出将是什么?
class Parent(object):
	x = 1

class Child1(Parent):
	pass

class Child2(Parent):
	pass

print Parent.x,Child1.x,Child2.x
Child.x = 2
print Parent.x,Child1.x,Child2.x
Child.x = 3
print Parent.x,Child1.x,Child2.x


/*js面试题*/
for(var i = 0; i < 10; i++) {
	setTimeout(function(){
		console.log(i)
	},1000);
}
### 你有几种方式将上述的输出变为0-9；

function aaa(){
      var a=b=10; 
}
aaa();
alert(a);
alert(b);


function aaa(){
  alert(a);
  var a=20;
}
aaa();

var a = 100;    
function test(){    
  var b = 2 * a;    
  var a = 200;    
  var c = a / 2;    
  alert(b);    
  alert(c);    
}    
test();

js数组去重 ， 怎么统计一个字符串里出现最多的字符
