# online-web-tools
收集了一些比较实用的Web在线工具。

## [Online JavaScript Beautifier](http://jsbeautifier.org/)
可以对JavaScript代码进行格式化，以方便阅读，当阅读别人格式比较乱的代码时尤其有用。

## [JSONLint](http://jsonlint.com/)
可以对JSON进行格式化，同时可以发现JSON中的语法错误，当调试内容较长的JSON时非常有用。我在开发时系统经常提示JSON语法错误，但是却找不出来，比如数组最后一个元素多了一个逗号，结果用JSONLint一就搞定了。

## [PlaceHolder](http://placehold.it/)
用来生成占位图片，比如开发时需要一张300x300的图片，但是美工还没有做图，所以我们可以用一张占位图进行开发调试，等图片做好替换即可，用法将图片尺寸跟在URL后面即可，如[http://placehold.it/300x300](http://placehold.it/300x300)即可生成一300x300的图片。

## [Regex Tester](http://regexpal.com/)
在线正则表达式测试工具，可以方便的测试我们的正则是否正确，进行在线调试。

## [Viewport Sizes](http://viewportsizes.com/)
可以查询所有主流移动设备的CSS像素，CSS像不是物理像素，比如iPhone6的物理像素是1334x750，而它的CSS像素是667x375。CSS像素主要是指移动浏览上的分辨率，所以在调试移动Web时就非常需要查各个移动设备的CSS像素。

## [阿里测](http://alibench.com/)
可以在线测试网站的性能，主要包括前端性能的方方面面，这个比YSlow或Chrome自带的audit更全名详细。当然阿里测也是基于[WebPagetest](http://www.webpagetest.org/)搭建的，大家也可以看看。

## [百度统计流量研究院](http://tongji.baidu.com/data/)
这是百度基于百度统计所覆盖的超过150万的站点的数据产生的报告数据，对于前端开发来说比较有用的数据主要包括：浏览器市场份额，分辨率使用情况，移动设备品牌占比，移动设备市场份额。这些数据有助于我们如何做浏览器兼容性测试，如何根据不同的分辨率做响应式开发等。比如IE6和IE7在中国的市场份额已经很低了，可以不用支持了，这是有数据有根据的了。需要说明的百度的数据主要基于国内的数据。

## [jsPerf: JavaScript performance playground](http://jsperf.com/)
这是一个标准的JS代码性能测试平台，比如如果觉得forEach比for循环快的话，可以在上面创建测试代码进行测试。它上面也有好多其它用户创建的基准测试代码。它比我们在自己的电脑上测试要准确得多，因为本地测试外部干扰因素较多。
