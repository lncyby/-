**iPhone CSS media query（媒体查询）**  

iPhone < 5:
@media screen and (device-aspect-ratio: 2/3) {}
 
iPhone 5:
@media screen and (device-aspect-ratio: 40/71) {}
 
iPhone 6:
@media screen and (device-aspect-ratio: 667/375) {}
 
iPhone 6Plus:
@media screen and (device-aspect-ratio: 16/9) {}
 
iPad:
@media screen and (device-aspect-ratio: 3/4) {}

**如何用jquery将页面所有元素边框设置为2px宽的虚线**
```
   jQuery (function ($)
    {
        $ ("*").css ("border", "2px dashed");
    })
```
**jquery点击按钮是隐藏图片**
$("#hide").click(function(){
  $("img").css("display","none");
});

**js 节点的增删改查**  

createElement() : 创建元素节点  
createTextNode() : 创建文本节点  
appendChild() : 将新节点追加到子节点的末尾  
replaceChild() :　将新节点替换旧节点　  

removeChild() : 移除节点  
insertBefore() : 将新节点插入到前面  
cloneNode() : 复制节点

**js 查找节点**
```
document.getElementById();
document.getElementsByTagName();
document.getElementsByName();
```
**对网站进行搜索引擎优化的方法是什么？**  

1、程序优化。编程者在开发程序的时候，尽量不使用非常用算法，不要出现代码错误，不要使程序机构混乱不堪。少使用FRAME框架结构，少使用图片、FLASH表达内容。还有的就是，要在程序源代码里要有“关键字”“描述”功能。语言结构简化，最好使用 CSS+DIV方式，而不是原先老旧的TABLE表格式。  

2、网站做成静态或者伪静态的。由于搜索引擎对现实存在的网页内容，容易搜索到，而对于数据库里的东西，很难搜索到，所以最好把页面做成静态的。当然，现在的网站很多是伪静态的，这个我在这里就不多说了。  

4、关键字词的密度和出现的位置。你的整体内容内应该包含有你内容关键字词。最好的法则是尽量使用语句和短语来包含你的关键字词，请记住在你的内容里注意你关键字词的密度。如你是拷贝别人的内容，也仔细检查一遍，适当的修改有可能你获得的流量比他都多。  

5、你网站url的结构。对于你网站URL的结构应当谨慎的考虑。尽量少使用带有？号以及其他字符的长元素出现，这样搜索引擎可能会理解为不友好的一种表现。最好使用带有明显倾向的字母来出现，或者使用国际上现在比较流行的一种标题－版权的写法。当然，这只是个建议。  

6、宝贵的mate元标签。尽量给你的网页写上特定的标签，标签里要包含你所做的关键字词。对于不同的网页内容，你需要自己琢磨出合适的标签以提高搜索引擎的机器人对你网站的覆盖范围，并通过此分辨出你网站的有效主题。最好是每一页有不同的标签来支撑。  

7、网站内容经常更新。内容最好是自己原创的，而不是从互联网上复制来的，即使复制，也得大量修改一下。对于高度重复的内容是没有价值的，搜索引擎不会收录。  

8、建立对外有效的链接和导入高质量的链接。相信这一点不用我过多的重复叙述，大家都能体会到他的好处。我需要重新强调一点的是：不要完全将外部链接导入到一个页面上，这样会导致搜索引擎的机器人在搜索的时候重复的过多搜索你的某一个页面。  

9、足够的耐心和坚韧的意志。一些SEOer在短期内看不到效果就放弃，而一些在短暂的获得排名之后又下去了变失去了信心。要知道，搜索引擎优化的过程是不断调整的过程，也不可能一蹴而就，一下子就有效果，而且搜索引擎不断的变化和加强着算法，被调整和掉下的可能性很大，需要有心理承受能力和自己一种信念。

**清除浮动的方式**
1、 父盒子设置一个高
2、 父盒子中的最后一个元素设置 claer:both;
3、 直接给父盒子设置 overflow:hidden;
4、 伪元素清除浮动
```
.clearfix::before,
.clearfix::after {
 content: "";
 height : 0;
 display:block;
 visibility:hidden;
 line-height: 0;
 clear : both;
}
.clearfix {
 zoom: 1; //兼容IE
}
```
### react 优缺点
比较现实的优点：能够实现服务器端的渲染，便于搜索引擎优化。这一点要比Backbone, Angular 1.x和Ember早期强能够很好的和现有的代码结合  
。React只是MVC中的View层，对于其他的部分并没有硬性要求。意味着很多公司在选择用Angular全部重构和用React部分重构的时候，选择了  
React部分重构因为一切都是component，所以代码更加模块化，重用代码更容易学起来非常容易，几个小时就可以入门因为强调只从this.props和  
this.state生成HTML，写起来bug比较少比较高大上的优点，就是大家在大会上会说的优点：因为用了virtual dom，所以性能很好因为强调只从  
this.props和this.state生成HTML，所以非常的functional programming  
缺点：并不是一个完整的框架，基本都需要加上ReactRouter和Flux才能写大型应用
