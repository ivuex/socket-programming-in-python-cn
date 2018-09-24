# Python 中的 Socket 编程

## 说明

本书翻译自 [realpython](https://realpython.com/) 网站上的文章教程 [Socket Programming in Python (Guide)](https://realpython.com/python-sockets/)，由于原文比较长，所以整理成了 Gitbook 方便阅读

## 关于作者

> Nathan Jennings 是 Real Python 教程网站团队的一员，他在很早之前就使用 C 语言开始了自己的编程生涯，但是最终发现了 Python，从 Web 应用和网络数据收集到网络安全，他喜欢任何 Pythonic 的东西

## 译者注

[译者](https://keelii.com/) 是一名前端工程师，平常会写很多的 JavaScript。但是当我使用 JavaScript 很长一段时间后，会对一些 *语言无关* 的编程概念感兴趣，比如：网络 socket 编程、异步/并发、线/进程等。然而恰好这些内容在 JavasScript 领域很少见

因为一直从事 Web 开发，所以理解了网络通信及其 socket 编程就理解了 Web 开发的某些本质。过程中我发现 Python 社区有很多我关心的东西，并且很多都是高质量的公开发布且开源的内容。

最近我发现了这篇文章，系统地从底层网络通信讲到了应用层协议及其 C/S 架构的应用程序，由浅入深，非常值得一读，因此推荐给大家

另外，由于本人水平所限，翻译过的内容难免出现偏差，如果你在阅读的过程中发现问题，请毫不忧虑的提醒我。或者有什么不理解的地方也可以开 issue 讨论

## 授权

本文（翻译版）通过了 real python 官方授权，原文版权归其所有，任何转载请联系他们

[开始吧](get-started.md)

{% raw %}
<script>
function insertDisqus() {
    var d = document, s = d.createElement('script');
    s.src = '//keelii-blog.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
}
setTimeout(insertDisqus, 100)
</script>
{% endraw %}