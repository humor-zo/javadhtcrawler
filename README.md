# javadhtcrawler
a dht crawler, include crawler and web
不会写文档，也不想写文档，但还是要让小白能够成功跑起来，所以还是不得不瞎扯一下。不懂的再QQ联系：331319769
运行环境
=================================
* 1.tomcat 8
* 2.mysql 5.1
* 3.redis
* 4.JDK 8

java jdk怎么装？tomcat怎么装？mysql？redis？谷歌去。
------------------
安装步骤：
===================
* 1.clone本项目到你的本地
* 2.eclipse导入本项目
* 3.修改src下的config.properties（数据库）和crawler.properties（爬虫参数）
* 4.war打包export导出项目
* 5.将war丢进tomcat的webapps目录下
* 6.进入tomcat的bin目录，执行：./startup.sh 启动tomcat

tomcat端口什么的自己去配吧，不懂的google。`需要注意的是：mysql需要修改默认的最大连接数，因为默认的是100，可能不够用（根据你自己在crawler.properties中配置而定）`
-----------------
