#####  组件
1. Nginx 1.14.0
2. JAVA 1.8
3. MYSQL 5.6
4. ReportServer 3.0.5

##### 目录
1. MySQL: /data/mysql
2. ReportServer: /data/wwwroot/

##### 用户名/密码信息
1. ReportServer:
   - root/root

2. MySQL : root/123456 (后续添加随机密码)

##### 配置文件
1. reportserver:
    -  /data/wwwroot/reportserver/WEB-INF/classes/persistence.properties (数据库连接)


##### ansible-playbook 可选参数

1. mysql_password: 123456 # mysql 默认密码
2. remote: no  # 是否开启远程
3. reportserver_url: http://xxx # reportserver下载地址