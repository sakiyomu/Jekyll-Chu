---
layout: post
title:  "Sublime Text 3必备插件"
date:   2016-02-22 08:22:00"
categories: 前端
tags: [前端, sublime, st3, 插件, plugin, package control, emmet, csscomb, utf8, trimmer, alignment, sass, scss, livereload, linter]
---

<h3><a href="https://packagecontrol.io/installation" target="_blank">Package Control</a></h3>  
![Package Control](/images/postimg/2016-02-22_01.gif)  
通俗易懂地说，这个是你在完成安装SublimeText后必须安装的东西。你问为什么？因为有了这个特殊的“插件包”，你可以很容易地安装、升级、删除，甚至非常方便地查看您已经安装在SublimeText中的包或插件的列表。它通过菜单和对应的行为使这些过程变得非常容易和有组织。
<br><br>

<h3><a href="http://emmet.io/" target="_blank">Emmet</a></h3>  
![Emmet](/images/postimg/2016-02-22_02.gif)  
概括地说，Emmet（前身就是以前大名鼎鼎的Zen Coding，这个如果你没听说和使用过，就悲哀了）是一个可以让你更快更高效地编写HTML和CSS，节省你大量时间的插件。怎么使用？你只需按约定的缩写形式书写而不用写整个代码，然后按“扩展”键，这些缩写就会自动扩展为对应的代码内容。 比如，你只需要输入 `((h4>a[rel=external])+p>img[width=500 height=320])*12` ，然后它会被扩展转换成12个列表项和紧随其后的图像。然后你就可以在此基础上再填写内容，就这么简单。 
<br><br>

<h3><a href="https://packagecontrol.io/packages/ConvertToUTF8" target="_blank">ConvertToUTF8</a></h3>  
![ConvertToUTF8](/images/postimg/2016-02-22_03.gif)  
解决中日韩以下编码文字乱码问题。（GBK, BIG5, EUC-KR, EUC-JP, Shift_JIS等）
<br><br>

<h3><a href="https://packagecontrol.io/packages/Codecs33" target="_blank">Codecs33</a></h3>  
为了让ConvertToUTF8更好的工作。
<br><br>

<h3><a href="http://csscomb.com/" target="_blank">CSScomb</a></h3>  
![CSScomb](/images/postimg/2016-02-22_04.gif)  
这是用来给CSS属性进行排序的格式化插件。如果你想保持的代码干净整洁，并且希望按一定的顺序排列（是不是有点强迫症了？），那么这个插件是一种有效解决的方案。特别是当你和其他有自己代码编写风格的开发者一同协作的时候。  

* User自定义文件下载：[CSScomb.sublime-settings](/files/CSScomb.sublime-settings)
* 存放路径：`/Packages/User/`
<br><br>

<h3><a href="https://github.com/jonlabelle/Trimmer" target="_blank">Trimmer</a></h3>  
![Trimmer](/images/postimg/2016-02-22_05.gif)  
你知道当你编写代码时，由于错误或别的某些原因，会产生一些不必要的空格。需要注意的是多余的空格有时也会造成错误。这个插件会自动删除这些不必要的空格，也可以删除空行，可以达到压缩css和js的效果。
<br><br>

<h3><a href="https://github.com/wbond/sublime_alignment" target="_blank">Alignment</a></h3>  
![Alignment](/images/postimg/2016-02-22_06.gif)  
这个插件让你能对齐你的代码，包括 PHP、CSS 和 Javascript。代码看起来更简洁和可读，便于编辑。可以自己设置以哪些符号对齐。

* User自定义文件下载：[Base File.sublime-settings](/files/Base File.sublime-settings)
* 存放路径：`/Packages/User/`
<br><br>

<h3><a href="https://github.com/kuroir/SCSS.tmbundle/zipball/SublimeText2" target="_blank">SASS</a></h3>  
![SASS](/images/postimg/2016-02-22_07.png)  
自动关联.sass、.scss文件。SASS文件语法高亮显示。  
直接在Package Control里搜索安装即可。  

1. 下载Sublime SCSS语法高亮包“[点击下载](https://github.com/kuroir/SCSS.tmbundle/zipball/SublimeText2)”
2. 将下载下来的文件包解压。
3. 打开Sublime安装目录下的Data → Packages目录
4. 将包放入打开的目录，重启Sublime，搞定。  
<br><br>

<h3><a href="https://github.com/jaumefontal/SASS-Build-SublimeText2" target="_blank">SASS Build</a></h3>  
SASS Build是一个编写CSS的预处理器。这个特别的插件将帮助你妥善构建包括压缩选项在内的SASS文件。一旦你安装了这个插件，你可以很容易地通过按Ctrl+B（MAC系统是Command+B）来启动它。   
可以将SCSS解析成CSS或压缩版CSS，在Sublime的菜单Tools → Build System里可以自由切换选择。
<br><br>

<h3><a href="https://github.com/alexnj/SublimeOnSaveBuild" target="_blank">SublimeOnSaveBuild</a></h3>  
SASS文件保存时就自动进行编译，免去SASS Build的手动操作。  
直接在Package Control里搜索安装即可。  
<br><br>

<h3><a href="https://github.com/livereload/LiveReload" target="_blank">LiveReload</a></h3>  
在本地写网页代码，通常都是保存以后再在浏览器里刷新一遍看看效果，刷新
这个可真是体力活，不过懒人也有福了，因为有了LiveReload。  
在Sublime Text里按下`Command+Shift+P`调出窗口，输入`install package`，之后输入`livereload`进行安装，重启Sublime Text。
然后安装浏览器扩展。LiveReload目前支持Safari、Chrome和Firefox三个浏览器的扩展，可以到<http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions->下载安装。
然后使用浏览器载入要修改的页面，点击LiveReload图标，当其中间圈圈显示为实心黑点时则为已经连接上可以正常使用了，之后每当你在Sublime Text里对源代码进行修改并保存后，LiveReload就会自动的刷新浏览器，你就可以马上查看到修改后的效果了。  

* User自定义文件下载：[LiveReload.sublime-settings](/files/LiveReload.sublime-settings)
* 存放路径：`/Packages/User/`
<br><br>

<h3><a href="https://github.com/SublimeLinter/SublimeLinter/tree/sublime-text-3" target="_blank">SublimeLinter</a></h3>  
![SASS](/images/postimg/2016-02-22_08.jpg)  
SublimeLinter是一个代码校验插件，它可以帮你找出错误或编写不规范的代码，支持C/C++、CoffeeScript、CSS、Git Commit Messages、Haml、HTML、Java、JavaScript、Lua、Objective-J、Perl、PHP、Puppet、Python、Ruby和XML语言。   
在使用SublimeLinter之前，你要安装相应的程序，详见<https://github.com/SublimeLinter/>，搜索：html、css、js。如果要校验JavaScript或CSS，还需要安装Node.js。
也可以在Package Control里搜索以下程序安装。

* SublimeLinter-html-tidy
* SublimeLinter-csslint
* SublimeLinter-jshint

<br>

<h5>部分插件介绍参考：</h5>

* _[20 个强大的 Sublime Text 插件](http://www.oschina.net/translate/20-powerful-
sublimetext-plugins)_
* _[Sublime Text 3 支持的热门插件推荐](http://www.imjeff.cn/blog/146/)_
	
	