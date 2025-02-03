# BlogX 后端代码

这是Fengfeng博客10代项目



最开始做七代博客的时候，是刚开始做go开发不到半年

表结构的搭建并不算是从0到1，没有原型，做前端页面的时候，一会儿一个想法

但是好在技术栈全面，和文档记录详细，还是帮助了不少人成功找到了自己心仪的工作



经过两年的技术沉淀，和gvb系列，gvd，fim，fai项目的授课经验

决定再从0到1开发一个博客系统

为此，我给它取了一个响当当的名字  BlogX，意为“博客十代”





## 项目需求

1. 管理员可以切换运行模式，社区、博客模式
2. 网站配置要尽可能全，直接运行不需要改代码就能变成自己的
3. 文章管理需要有人工审核机制，可以有效保障内容安全，同时也留了一个免审核功能
4. 私信功能全面升级，用户可给喜欢的博主发私信，好友关系分为 陌生人 已关注  粉丝  好友
5. 消息通知更加全面，包括评论，赞和收藏，系统通知
6. 收藏夹、文章分类功能，可以通过此功能整理同类型文章
7. 个人主页，每个用户都可以选择不同的样式
8. 用户发布文章，可以开启是否可评论
9. 登录注册功能，可定制化是否使用qq登录，邮箱注册，是否显示图形验证码
10. 文章最少只需要标题和正文，可大大简化发布流程
11. 要接入AI，要有差异化

    可以做AI知识库，根据用户输入的内容，在全站文章中AI匹配

    还可以在发布文章的时候，分析文章适合的标签，分类，标题
12. 要能实现前端发版之后，线上能够自动刷新
13. 日志的记录要尽可能全面，日志方法的使用要简单
14. 数据库优化方面，索引优化，主从同步、读写分离，水平分表
15. 可以不需要es依赖，对应的搜索功能则需要对应的服务降级
16. 一键部署，部署流程要尽可能简单



## 项目相关技术栈

后端：

gin，gorm，redis，mysql，websocket， SSE，elasticsearch，docker-compose

前端：

vue3/ts，arco-desgin

## 后端默认用户名密码
```text
admin/1234
```



## 你将学到

1. 使用ws实现在线用户的即时通讯
2. mysql和es的数据同步
3. qq登录的相关知识点
4. 编写docker-compose，实现便捷部署



## 表结构

![](https://image.fengfengzhidao.com/pic/20240926232427.png)



## 原型

![](https://image.fengfengzhidao.com/rj_0912/20240926144115.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926144221.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926144301.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926144339.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926144456.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926144718.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926144752.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926144826.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926144856.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926145011.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926144954.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926145040.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926145116.png)



![](https://image.fengfengzhidao.com/rj_0912/20240930110631.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926145312.png)



![](https://image.fengfengzhidao.com/rj_0912/20240926145345.png)