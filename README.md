Work In Process
==

导航请移步到: http://python-cn.github.io/guide

说明
--

这里只包含等待开发的Todo List. 会尽量更新到最新状态.

有兴趣参与者请使用: [teambition](http://tburl.in/aba6fdf0)去获取最新的任务列表. 防止任务已被认领造成重复.

沟通请使用: [pythoncn-slack](https://pythoncn.slack.com)(需要邀请, 请发邮件到ciici123@gamil.com, 或者联系组内其他成员),
参与开发者才会被通过(slack没有灌水区)，请谨慎加入

## 学习准备 - 假如你觉得你还没有能力做下面的todo list, 可以先准备以下一些知识, 将来会用到

- react
- oath2
- select2

PS: 其他的firelfy的依赖的列表在这里: http://python-cn.github.io/guide/#/post/used.md

## Todo List

- [] 主题的分类model, 早起可以是先插入的一些固定数据,比如devops, web开发, 爬虫..(选项不重要, 要有后台的支持)
- [] 主题的分类model的接口. 前端可以通过ajax调用这个url 获得全部的分类信息: 分类id, 分类名, 分类描述
- [] 创建主题时候可以通过select2选择分类, 效果类似meta.discourse.org创建主题的分类下拉框效果(可以只是功能, 没有css样式)
- [] 创建请求中会带上分类的参数, 后端save的时候会生成含有分类的主题(Post)
- [] 首页渲染时, 能获得某主题对应的分类.
- [] 设计阅读量的实现, 就是刷新一下页面, 阅读量就会+1
- [] 让每个主题页面(http://web:port/post/post_id/)里面显示出评论的内容.
- [] 首页注册和登陆页面的浏览器兼容性(chrome下正常, FF下不正常)
- [] 注册页面当用户名/密码/邮箱都有正确输入的时候让`注册`按钮变成enable
