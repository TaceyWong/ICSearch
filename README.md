# ICSearch


目标：

通用型web爬虫服务框架，要满足以下特点：

+ 支持Web-Dash以管理爬虫，并提供同等功能的HTTP/RPG接口
+ 方便本机开发
+ 方便协作开发
+ 方便生产环境测试
+ 方便部署
+ 支持热更新，暨在不重启的情况下发布新spider
+ 支持以下模式及各模式模板生成
	+ 纯JSON/XML配置模式
	+ JSON + EXCUTOR 模式
	+ 继承类模式
	+ 自由适配模式

+ 支持分布式node×单机进程/线程/协成控制
+ 支持一般日志、异常日志统一搜集管理，且方案可配置


具体使用主要有三层 icspider框架层 -> 通用业务层 -> 具体爬虫层

icspider提供基础服务，通用业务层根据实际业务使用基础服务编写通用逻辑，具体爬虫编写实际的爬虫逻辑

 
