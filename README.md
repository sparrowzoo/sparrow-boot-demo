# 项目启动示例
## 编译
```agsl
mvn clean package
```
## 运行
```agsl
cd target
tar -xvf sparrow-boot-demo.tar.gz
cd sparrow-boot-demo
//启动
sh start.sh start 
//停止 
sh start.sh stop
```

# 注意事项
1. 脚本中的端口号需要修改为项目启动的端口号
```agsl
APP_PORT=9999
```
2. 脚本中的home 修改要修改为上传后的根目录
```agsl
APP_HOME=/home/admin/app/sparrow-boot-demo # 从package.tgz中解压出来的jar包放到这个目录下
```

