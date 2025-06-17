---
title: 不着调的大疯狗
permalink: /about/
layout: page
excerpt: 
comments: true
---


**大哥你玩摇滚，你玩他有啥用啊？？？**

<!-- Valine 评论区 -->
<div id="vcomments"></div>
<script src="https://cdn.jsdelivr.net/npm/leancloud-storage@4.13.2/dist/av-min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/valine@1.5.1/dist/Valine.min.js"></script>
<script>
  new Valine({
    el: '#vcomments',
    appId: 'TKEpqf2EF1Mb240Pkw1bLI3i-MdYXbMMI',          // 替换为你的 LeanCloud AppID
    appKey: 'MuJkuns5jj7ASufxUVaE4rc0',        // 替换为你的 LeanCloud AppKey
    placeholder: '请输入评论...', // 评论框占位符
    path: window.location.pathname, // 使用文章路径作为唯一标识
    avatar: 'mp',                // 头像样式（'mp'、'identicon' 等）
    pageSize: 10,                // 评论分页数量
    lang: 'zh-cn',               // 语言（中文简体）
  });
</script>


**✨ Contact me ✨**

- {{ site.author.email }}
- github.com/{{ site.author.github }}
