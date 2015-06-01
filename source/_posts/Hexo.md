Hexo 使用
---
Welcome to [Hexo](http://hexo.io/)!

## 插件


### 多说

 
显示评论: [duoshuo.com](http://duoshuo.com/create-site/)

```
1.进入多说官网注册.
2.复制通用代码保存到博客模板
3.将通用代码中的：
请将此处替换成文章在你的站点中的ID 替换为 <%= page.path %>
请替换成文章的标题 替换为 <%= page.title %>
请替换成文章的网址 替换为 <%= page.permalink %>
效果如下:
<div class="ds-thread" data-thread-key="<%= page.path %>" data-title="<%= page.title %>" data-url="<%= page.permalink %>"></div>
```
![1](/img/1.png)


