# oc-install
根据快速部署需求，特地为您打包，可以快速本地部署，查看效果！

### 环境要求
```
 jdk 1.8
 mysql 6.5以上
 配置host  IP(oc-server的IP地址) im.jshii.com.cn
```
### 初始化数据
```
  Mysql 导入oc_db.sql 执行(注意配置用户或者密码为：root/123456)
```
### oc-server部署步骤
```
 创建logs目录
 执行启动命令：java -jar oc-server.jar --spring.profiles.active=dev > ./logs/console.log &
 注意：以上操作请在jar包当前目录
``` 
 
### 客服工作台
```
 点击安装即可，附带测试账号：test/123456
```

### 访客端请求地址
```
 http://im.jshii.com.cn:8080/front/pc/chat.html?ttc=1&skc=1
```


### 通过上述操作 即可简单应用 ###
```
感谢您的使用！
有问题欢迎咨询 QQ群: 606173512
```
 
