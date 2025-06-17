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
<script src="//code.bdstatic.com/npm/leancloud-storage@4.12.0/dist/av-min.js"></script>
<script src='https://unpkg.com/valine@1.5.1/dist/Valine.min.js'></script>
<script>
  new Valine({
    el: '#vcomments',
    appId: 'v9FFeF48UwudquFr7xzz3wLc-gzGzoHsz',          // 替换为你的 LeanCloud AppID
    appKey: 'bKcxy6P4pcSHu4pY1tvoVRpq',        // 替换为你的 LeanCloud AppKey
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
