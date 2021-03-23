
服务端
项目后端环境

JDK1.8
Mysql5.7
Redis
IDEA编译器
Lombox插件（百度一下）
ElasticSearch 6.x
RabbitMQ
IDEA编译器



部署步骤：

创建数据库dbblog，并导入dbblog-backend -> db里的所有sql文件
修改dbblog-backend -> dbblog-> dbblog-core里的application-*.yml的数据库连接、redis连接、ElasticSearch连接、RabbitMQ连接
导入项目，并且运行dbblog-backend -> dbblog-search -> BlogApplication里的main方法