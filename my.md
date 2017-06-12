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

**js 查找节点 **
```
document.getElementById();
document.getElementsByTagName();
document.getElementsByName();
```
