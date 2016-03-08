# zhihu-fuli
过滤知乎当前页面的图片，以瀑布流形式展现，如果显示不正常，请使用最新版chrome

#原理说明：
<http://blog.hjk.im/zhihu-fuli.html>

#使用方式
- 打开知乎的问题页面，比如<http://www.zhihu.com/question/24214727>
- 按下F12（Mac系统快捷键好像不同，可以右击页面审查元素）打开console
- 输入`$.get('http://rawgit.com/0xHJK/zhihu-fuli/master/zhihufuli.js.png',function(res){eval(res)})`
- 如果提示错误，则把zhihufuli.min.js里面的代码复制到console里面执行
![使用方式](./preview/option.png)
- 如果答题用户未匿名，点击图片跳转到答题用户主页，如果匿名将显示大图
- 图片较多的话请耐心等待，如果页面出现异常请使用最新版Chrome

#预览效果
同样是细腿，为什么有的看起来就很性感？有的就感觉一般呢？秘密到底在哪里？
<http://www.zhihu.com/question/32680596>
![同样是细腿，为什么有的看起来就很性感？有的就感觉一般呢？秘密到底在哪里？](./preview/32680596.png)

女生的美腿是怎样炼成的？成长期要注意什么？
<http://www.zhihu.com/question/20399991>
![女生的美腿是怎样炼成的？成长期要注意什么？](./preview/20399991.png)

大胸妹子如何挑选合身又好看的比基尼？
<http://www.zhihu.com/question/24214727>
![大胸妹子如何挑选合身又好看的比基尼？](./preview/24214727.png)




