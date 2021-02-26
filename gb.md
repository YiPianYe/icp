---
title: gb
permalink: gb/
profile: true
---

## 留言

var gitalk = new Gitalk({
  clientID: '6c626877a33954d5b9d1', // GitHub Application Client ID
  clientSecret: 'd19a3183486c87a019377c9abf561cbef5d73766', // GitHub Application Client Secret
  repo: 'gitalk-comment'      // 存放评论的仓库
  owner: 'qinghongjiao',          // 仓库的创建者，
  admin: ['qinghongjiao'],        // 如果仓库有多个人可以操作，那么在这里以数组形式写出
  id: location.pathname,      // 用于标记评论是哪个页面的，确保唯一，并且长度小于50
})

gitalk.render('gitalk-container');    // 渲染Gitalk评论组件


{% include footer.html %}
