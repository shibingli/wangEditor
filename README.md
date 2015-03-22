0. 本次更新说明
===
更新时间为：2015-03-20，更新版本为1.3版。本次更新的主要内容：<br/>
第一，对代码做了一次彻底的重构，更加面向对象的编程；<br>
第二，重构UI界面，增加易用性；
第三，增加插入简洁代码的功能；

1. 介绍
===
<b>wangEditor——轻量级web富文本编辑器，配置方便，使用简单</b>。支持IE7+浏览器。
![](http://images.cnitblog.com/blog2015/138012/201503/222048140317441.png)

2. 如何使用？
===
引用wangEditor.css、jquery.js和wangEditor.js之后，一行代码即可把textarea变为富文本框，简单应用。
```javascript
$(function(){
    $('#textarea1').wangEditor();
});
```
具体的应用，可下载源码，源码中相应的demo页面有详细使用说明。
* <code>demo.html</code> （demo演示）
* <code>demo-basic.html</code> （基本配置说明）
* <code>demo-initContent.html</code> （配置初始化时要显示的内容）
* <code>demo-hideMenuConfig.html</code> （配置要隐藏的菜单按钮）
* <code>demo-menuConfig.html</code> （配置要显示的菜单按钮，其他的隐藏）
* <code>demo-change.html</code> （配置change事件）

3. 自定义主题颜色
===
wangEditor默认的主题为灰色，你也可以自己定义自己喜欢的颜色。<br>
找到<code>css/wangEditor-1.3.less</code>文件，搜到<code>begin：颜色配置</code>关键字，然后你就可以找到wangEditor的所有颜色配置。在这里自由发挥的修改吧！<br>
不要忘记，最后要把<code>less</code>编译成<code>css</code>。

4. 交流
===
交流QQ群：<b>164999061</b> <br />
二次开发联系：<b>wangfupeng1988#163.com（#->@）</b>