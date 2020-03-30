# Web 版的 **nmon Analyser**

模仿 Nmon-Analyser（Excel版本）的 Web 版本。

原本做好了就放 [线上](http://nmon.leixipaopao.com) 没咋去管了，今天才发现原来线上的版本还引用了一个访问很慢的 css 文件，还一直以为是我服务器的带宽太低了。。。

之前也想着做一个离线版本，拖到现在。。



线上的版本是前后端分离的，为了偷个懒，我就继续用 [esc](https://github.com/mjibson/esc) 把前端都给打包进来了。

所以呢，访问页面的端口也是被固定了

[下载地址](https://github.com/ElectricBubble/nmon-analyser-releases/releases/latest)

执行后，浏览器 (Chrome/Safari) [访问](http://localhost:10001/nmon/) `http://localhost:10001/nmon/`

通过左上角的上传 nmon 文件 <img src="https://raw.githubusercontent.com/ElectricBubble/ImageHosting/master/img/20200330171254.png" style="zoom:50%;" />

解析完毕后，旁边的 tab栏 会显示全部分类，切换可看到对应的图表  

![](https://raw.githubusercontent.com/ElectricBubble/ImageHosting/master/img/20200330171552.png)



对应图表📈的底下，还有一个简陋的对应指标的平均值

  

  



<font size=1>因为代码写的感觉太一般。。。就不好意思放源码了。。</font>
