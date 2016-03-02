---
layout: post
title:  "Emmet必会快捷键"
date:   2016-02-23 11:52:00
categories: 前端
tags: [前端, Emmet, sublime, st3, 快捷键, shortcuts]
---
<style>
h4 {
    background-color: #333333;
    border-left: 5px solid #336699;
    font-size: 120%;
    margin: 5px 0;
    padding: 10px;
    color: #fff;
}
h4 a:after {
    content: url("http://1.bp.blogspot.com/-0s6JgzUybPE/T8hA2CRW6NI/AAAAAAAAAQs/848ih6zCa0U/s1600/target_blank.png");
    margin: 0 2px;
}
span.key {
    background-color: #eee;
    border: 5px outset #eeeeee;
    border-radius: 8px;
    color: black;
    line-height: 2.5em;
    margin: 2px;
    padding: 2px 8px;
}
</style>

<h4>打开Package Control</h4>
<p><span class="key">⌘</span> + <span class="key">⇧</span> + <span class="key">P</span>（Macintosh）<br>
<span class="key">Ctrl</span> + <span class="key">Shift</span> + <span class="key">P</span>（Windows）</p>
<p>以下命令可以打开Package Control后输入名称执行或查看快捷键。</p>

<h4>现有内容添加标签（<a href="http://docs.emmet.io/actions/wrap-with-abbreviation/" target="_blank">Wrap with Abbreviation</a>）</h4>
<p>在已经写好的内容上套上需要的标签。快捷键打开输入条后自己输入所需要的标签，一些特殊写法请参考链接里的官方说明。<br>
<span class="key">⌃</span> + <span class="key">W</span> 或 <span class="key">⌃</span> + <span class="key">⌥</span> + <span class="key">↩</span>（Macintosh）<br>
<span class="key">Ctrl</span> + <span class="key">W</span> 或 <span class="key">Ctrl</span> + <span class="key">Alt</span> + <span class="key">Enter</span>（Windows）</p>

<h4>扩大选择范围（<a href="http://docs.emmet.io/actions/match-pair/" target="_blank">Match Tag Pair</a>）</h4>
<p>每执行一次就向外多选中一层。<br>
<span class="key">⌃</span> + <span class="key">D</span>（Macintosh）<br>
<span class="key">Ctrl</span> + <span class="key">D</span>（Windows）</p>

<h4>注释内容（<a href="http://docs.emmet.io/actions/toggle-comment/" target="_blank">Toggle Comment</a>）</h4>
<p>将选中的内容变成注释。<br>
<span class="key">⌘</span> + <span class="key">/</span>（Macintosh）<br>
<span class="key">Ctrl</span> + <span class="key">/</span>（Windows）</p>

<h4>开/闭标签位置相互跳转（<a href="http://docs.emmet.io/actions/go-to-pair/" target="_blank">Go to Matching Pair</a>）</h4>
<p>用来查看标签对应关系很方便。<br>
<span class="key">⌃</span> + <span class="key">⇧</span> + <span class="key">T</span>（Macintosh）<br>
<span class="key">Ctrl</span> + <span class="key">Shift</span> + <span class="key">T</span>（Windows）</p>

<h4>删除标签（<a href="http://docs.emmet.io/actions/remove-tag/" target="_blank">Remove Tag</a>）</h4>
<p>默认快捷键不方便，忘了它吧。建议自定义快捷键如下：<br>
<span class="key">⌘</span> + <span class="key">R</span>（Macintosh）<br>
<span class="key">Ctrl</span> + <span class="key">R</span>（Windows）<br>
（自定义方法问我）</p>

<h4>获取图片尺寸（<a href="http://docs.emmet.io/actions/update-image-size/" target="_blank">Update Image Size</a>）</h4>
<p>可以自动获取图片的实际尺寸导入到HTML，非常方便。<br>
<span class="key">⌃</span> + <span class="key">⇧</span> + <span class="key">I</span>（Macintosh）<br>
<span class="key">Ctrl</span> + <span class="key">Shift</span> + <span class="key">I</span>（Windows）</p>

<h4>图片转Base64（<a href="http://docs.emmet.io/actions/base64/" target="_blank">Encode/Decode Image to data:URL</a>）</h4>
<p>直接在HTML文件里操作，图片需要转Base64的话非常方便。<br>
<span class="key">⌃</span> + <span class="key">⇧</span> + <span class="key">D</span>（Macintosh）<br>
<span class="key">Ctrl</span> + <span class="key">Shift</span> + <span class="key">D</span>（Windows）</p>

<h4>整行代码上下移动</h4>
<p>将光标所在行代码上下移动。<br>
<span class="key">⌘</span> + <span class="key">⌃</span> + <span class="key">↑</span> or <span class="key">↓</span>（Macintosh）</p>

<h4>CSScomb快捷键</h4>
<p>将CSS代码统一排序并统一格式。（需要CSScomb插件）<br>
<span class="key">⌃</span> + <span class="key">↑</span> + <span class="key">C</span>（Macintosh）<br>
<span class="key">Ctrl</span> + <span class="key">Shift</span> + <span class="key">C</span>（Windows）</p>

<h4>Alignment快捷键</h4>
<p>将PHP、CSS和Javascript代码按设置的标点符号对齐。（需要Alignment插件）<br>
<span class="key">⌃</span> + <span class="key">↑</span> + <span class="key">A</span>（Macintosh）<br>
<span class="key">Ctrl</span> + <span class="key">Shift</span> + <span class="key">A</span>（Windows）</p>



<h5>参考网页：</h5>

* _[Emmet：HTML/CSS代码快速编写神器](http://www.iteye.com/news/27580)_
* _[Emmet快捷方式查询](http://emmet.evget.com/)_
* _[SublimeText2のEmmet（Zen-Coding）カスタマイズ](http://qiita.com/sygnas/items/d609790b25989c6de703)_
* _[Wrap with Abbreviation](http://docs.emmet.io/actions/wrap-with-abbreviation/)_
* _[[SublimeText]Emmetを使いこなすためのショートカットキー](http://wada811.blogspot.com/2013/03/sublime-text-2-emmet-shortcut-key.html)_


