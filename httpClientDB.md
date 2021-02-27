## 概述
飞尚推送软件，该软件为命令行程序，包含以下文件，需要在命令行下运行  
```
bearer
cfg.ini
httpClientDB.exe
libgcc_s_dw2-1.dll
libstdc++-6.dll
libwinpthread-1.dll
Qt5Core.dll
Qt5Network.dll
Qt5Sql.dll
sqldrivers
t.txt
translations
```


## 使用步骤
1. 修改配置文件  

||描述|例子|  
|----|----|----|  
URL|推送地址|http://182.137.14.195:9090/scbd/sensorData/send
USR|数据库用户名|sa
PWD|数据库密码|xqxq#1234
DBNAME|数据库名|t500
PORT|数据库端口号|1433
HOST|数据库地址|127.0.0.1
2. 在命令行下运行httpClientDB.exe