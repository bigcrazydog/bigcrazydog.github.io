---
title: 不着调的大疯狗
permalink: /about/
layout: page
excerpt: 
comments: true
---


**大哥你玩摇滚，你玩他有啥用啊？？？**

<div id="gitalk-container"></div>
<script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css">
<script>
  const gitalk = new Gitalk({
    clientID: 'Ov23livvaVpP0wqyPP3F',
    clientSecret: '19247d72a81ec83ac1606b6a48fda91328a458b6',
    repo: 'bigcrazydog',       // 存储评论的仓库
    owner: 'bigcrazydog',
    admin: ['bigcrazydog'],
    id: window.location.pathname,  // 使用文章路径作为唯一标识
  });
  gitalk.render('gitalk-container');
</script>


**✨ Contact me ✨**

- {{ site.author.email }}
- github.com/{{ site.author.github }}
