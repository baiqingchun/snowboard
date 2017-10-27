# snowboard
下面是mac安装方式
#运行命令
```
./snowboard 
```
```
sudo cp snowboard /usr/local/bin
```

查看是否snowboard安装成功，运行命令
```
snowboard
```

里面有备份，那是最早的模板文件，还有t文件那是修改后的模板文件。
比最早的多了几个功能：
   1，点击请求，在控制台里可以查看请求
   2，请求过程中可以发送body的请求。
   
还有一个t1文件正在开发中，自定义body参数，还没有成功。

生成文档命令
```
snowboard html -t t.html -s record.apib
```
会默认生成一个index.html
直接访问    http://127.0.0.1:8088/

