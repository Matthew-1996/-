# 学习资料和方法
- [一个不怎么滴教学视频](https://www.bilibili.com/video/BV1t7411A7cL?from=search&seid=6512466458755770239)
- [一个neo4j+d3.js的个人使用记录，比较杂乱，但完整](https://search.bilibili.com/all?keyword=neo4j&from_source=webtop_search&spm_id_from=333.851)
- [武汉大学的neo4j教学视频](https://www.bilibili.com/video/BV1Si4y147K8?from=search&seid=6512466458755770239)：这个视频感觉比较基础易懂，可以先用它上手

先根据[武汉大学的neo4j教学视频](https://www.bilibili.com/video/BV1Si4y147K8?from=search&seid=6512466458755770239)，尝试一下批量导入实体和关系吧  


同时，我觉得可以从，笔记共现词的图入手：  
- 概念：笔记词、标签。。。
- 实体：词{词}
- 关系：共现{共现次数}

或者，我可以以笔记为实体建数据库吗？
- 概念：笔记的分类；或者是视频、图文
- 实体：笔记{词：}
- 关系：作者发布笔记、转评赞用户。。。。

那第二种方案，是一个更完整的数据库。目前我还不确定，在这种情况下，能不能单独抽取出词的共现。