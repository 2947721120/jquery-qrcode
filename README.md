# jquery.qrcode.js

<a href='http://jeromeetienne.github.com/jquery-qrcode'>jquery.qrcode.js</a>
is *jquery plugin for a pure browser qrcode generation*.
它允许您轻松地添加QR码到您的网页。

它是独立的，在缩小+ gzip小于4K，没有图像下载。

它不依赖于外部服务，或在加载时添加延迟。

它是基于一个 <a href='http://www.d-project.com/qrcode/index.html'>library</a>
建立QR码在各种语言. <a href='http://jeromeetienne.github.com/jquery-qrcode'>jquery.qrcode.js</a>包

它可以很容易地包含在你自己的代码中。

显示，不要说，这里是一个<a href='https://github.com/jeromeetienne/jquery-qrcode/blob/master/examples/basic.html'>example</a>

## 如何使用它

让我走你通过它。首先将它包含在您的网页中，与通常的脚本标记
    
    <script type="text/javascript" src="jquery.qrcode.min.js"></script>

然后创建一个DOM元素会包含生成的QR码图像。让我们说

一个div

    <div id="qrcode"></div>

然后你添加 *qrcode* 在这个容器中

    jquery('#qrcode').qrcode("this plugin is great");

这是。看到它 <a href='examples/basic.html'>live</a>.

你可以设置高度和宽度的生成QRCODE：

    jquery('#qrcode').qrcode({width: 64,height: 64,text: "size doesn't matter"});


## Conclusion
<a href='http://jeromeetienne.github.com/jquery-qrcode'>jquery.qrcode.js</a> is available on github
<a href='https://github.com/jeromeetienne/jquery-qrcode'>here</a>
under <a href='https://github.com/jeromeetienne/jquery-qrcode/blob/master/MIT-LICENSE.txt'>MIT license</a>.
If you hit bugs, fill issues on github.
Feel free to fork, modify and have fun with it :)
