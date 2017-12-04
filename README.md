# 个人信息
- 张金龙 / 男 / 1988 / 江西赣州 / 汉 / 深圳蛇口南油大厦
- 本科 / 软件工程 / 华东交通大学 / cet-4
- 工作年限: 7年
- 手机：185030002551 / 微信：zjl_jx / 邮箱：zjl_jx@126.com 
- Github: https://github.com/dillonnet
- 热爱生活，喜欢篮球、羽毛球活动

# 技能清单
- 7年.net平台开发经验，熟悉MVC、WebApi、Ado、EF、Memcached、Owin
- 熟悉.Net Core、EF Core、WebSocket、Dapper、IOC 、AOP、OAuth2.0
- 熟悉Javascript、CSS、HTML、jQuery、Bootstrap
- 熟悉ES6、Vue、Vuex、React、Redux、Webpack.
- 熟悉SQL Server、My Sql.了解MongoDB、PgSQL、InfluxDb. 熟悉数据库管理和调优
- 熟练使用git, 熟悉敏捷开发流程，熟悉微信公众号开发
- 了解Linux、Nginx、Python、Scrapy
- 了解Docker、Kubernetes、MicroServices、Redis、Rabbitmq
- 了解网站性能优化，高并发


# 项目经历
**深圳中佳科技有限公司 技术经理— 2016.10月-至今**

中佳科技是一家移动互联网公司[（http://www.zhongjiatech.com/）](http://www.zhongjiatech.com/)。

公司框架选用ASP.NET Core + MVC + Web API + EF Core + DI + AOP。

- 负责中佳看我装、嘀家、德金物业、中策大数据app开发和上线
    - 看我装是业主在业主端下单，装修公司在装修端抢单模式的App,实现了施工进度实时查看、图纸管理、装修直播、材料报价、实时沟通等功能
    - 嘀家App是一个智慧社区App,实现了app远程开锁、蓝牙开锁、ic开锁、在线报修等功能
    - 德金物业App是实现了水电录入、自动订单生成、在线缴费、报修等功能

- 负责技术部日常管理 
    - 领导所有项目的需求分析，原型讨论，并给出关键性指导建议
    - 组织部门成员开会，每日站立日会各自工作情况，解决项目开发中发现的问题，把控整个项目的进度
- 负责技术框架的搭建与落地
    - 简单三层. API采有RESTful架构，接口认证采用JWT.通过Swagger UI提供API文档，完善的接口注释减少与前端人员的沟通
    - 封装了基础服务代码，如：常用扩展方法、缓存、队列、日志、性能度量,并搭建内网nuget服务器
    - 封装了调用第三方服务平台代码，如：短信发送，消息推送，环信聊天.
    - 后台前端一开始使用React+Dva+Ant Design框架，后经过实践调整选用Vue2.0+Element UI,项目采用前后端分离，前端开始mock数据进行代码开发.
    - 监控所有项目的运行情况，实时的报错监控，App.Metrics+InfluxDB+Grafana。
- 负责项目流程的管控
    - 公司代码用Git管理，代码放在码云上，开发分支流程采用Git Flow
    - 提交PR后，检查同事的代码，严格审核代码质量，指出代码问题，合并分支.
    - 选用阿里云服务器，嘀家项目采用Ubuntu Linux + My SQL + Nginx,其它项目采用IIS + SQL Server 部署采用Jenkins一键自动部署到测试或生产环境
    - 处理日常Bug和生产发生的紧急问题
- 负责基于Scapy（Python语言） 的工程项目的爬虫开发


**深圳八爪网络有限公司 .net高级工程师— 2015.8月-2016.10月**

深圳八爪网络科技有限公司是一家致力于通过互联网技术改变招聘效率与个人求职体验的科技公司。目前拥有猎必得，雇得易，云猎等品牌的互联网平台产品、互联网化软件产品。[（http://www.liebide.com/）](http://www.liebide.com/)

公司采用ASP.NET + MVC + EF + Memcached框架，数据库Sql Server。 采用Git源代码管理，Jira+Bitbucket+Bamboo 实现公司流程自动化管理、部署。

- 严格按照scrum开发流程，按时按质完成版本的迭代
- 负责公司百万简历的检索
    - 搭建ElasticSearch + IK分词检索服务器，向外暴露API供客户端调用
    - 热更新分词词典，实时监控搜索结果，优化搜索
- 负责猎必得项目开发和后台日常运营
    - 猎必得云币系统、简历搜索功能的功能，提高简历搜索速度和准备性.
    - 微信公众号开发，绑定账号、红包管理
    - 猎必得后台开发，采用VUE提高后台人员前端的开发速度
- 参与了易猎项目几个版本的迭代


**深圳红酒世界网新媒体有限公司  .net工程师— 2012.6月-2015.6**

红酒世界网 是全球葡萄酒搜索平台，旗下有红酒知识平台和红酒电商平台。[（ http://www.wine-world.com/）](http://www.wine-world.com/)

公司框架选用ASP.NET + MVC

- 负责国外百万红酒数据的抓取
    - 负责多个国外网站红酒数据的抓取、清洗
    - 通过频率、IP池、代理等应对一些网站的反爬
- 负责公司网站SEO优化
    - 通过优化SEO，使红酒知识平台网站红酒、葡萄酒等关键词Baidu、Google搜索排名第一
- 负责红酒数据的检索
    - 通过Lucene.Net + Pangu分词进行红酒数据的检索
    - 调整红酒数据分词词典，定时执行红酒数据索引
- 负责红酒电商平台架构和数据库设计
    - 吸取开源项目Nopcommerce项目知识，重新调整公司架构，采用MVC + EF6
    - 使用Power Designer进行整个电商数据库的设计，与同事讨论优化数据库结构

# 个人评价
- 我对自己定价：全栈工程师，主攻后端，第二语言前端 ，同时在其它方面打打辅助
- 工作态度：第一，要高效并完美的完成自己的本职工作.第二，与其他同事交流学习，互相提升，积极参与解决项目中遇到的疑难杂症
- 克服困难：不用百度，遇到技术问题会去Google、Stackoverflow上寻找答案.在用新框架前会去详细阅读英文文档并实践. 