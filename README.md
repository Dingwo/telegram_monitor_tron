# telegram_monitor_tronusdt地址监控机器人 
usdt地址监控机器人 
usdt address monitoring robot

主要功能：
1.监听USDT/TRC20 链入账出账通知

2.查询USDT/TRC20 余额

3.可以添加和删除需要监控地址

4.可授权给制定的id或者地址进行监控


使用方法：

下载本项目源码导入数据库结构

修改telegram.yaml配置文件中的token和 dsn数据库连接
<code>
telegram:
  token: 6158073xxx:AAEyx2sB9qoJSuL_cW460E7Mtitou9dxxxx
  db:
    type: mysql  
    dsn: "root@tcp(127.0.0.1:3306)/tgxxx?charset=utf8&parseTime=True&loc=Local"
    maxIdle: 100
    maxOpen: 200
    timeout: 30
    ready_only:
   </code> 
启动命令

 # ./minitor_tron 
 
 #tail -f nohup.out  
 
演示版本：

私人定制：

Telegram：[@lianwo ](https://t.me/lianwo)

群组：

机器人网站源码开发搭建/ TG会员/TRX兑换/地址监控/能量租赁/供需发布机器人 等各类机器人 详询客服
客 服：@lianwo  客 服：@dingwo

频 道：@sousuowo  群 组：@tianjiawo

机器人：@TianTianKJBot   官 网：https://52wzq.cc
