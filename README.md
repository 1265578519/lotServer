## 用户安装  
 ~~（脚本内置许可证的接口为我自己的接口了，有效期9999年那种 笑）~~
 > 常规自动安装（推荐，自动检测内核）
```
bash <(wget --no-check-certificate -qO-  https://raw.githubusercontent.com/1265578519/lotServer/main/lotServerInstall.sh) install
```

 > 指定内核安装
```
bash <(wget --no-check-certificate -qO-  https://raw.githubusercontent.com/1265578519/lotServer/main/lotServerInstall.sh) install 2.6.32-754.18.2.el6.x86_64
```

 > 完全卸载
```
bash <(wget --no-check-certificate -qO-  https://raw.githubusercontent.com/1265578519/lotServer/main/lotServerInstall.sh) uninstall
```
***
***
## 使用方法
- 启动命令 /appex/bin/lotServer.sh start
- 停止加速 /appex/bin/lotServer.sh stop
- 状态查询 /appex/bin/lotServer.sh status
- 重新启动 /appex/bin/lotServer.sh restart
***
***
 > Centos 7开机启动
```
echo "/usr/bin/sh /appex/bin/lotServer.sh restart" >> /etc/rc.d/rc.local
```
