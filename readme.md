说明：

增加了Adblock的easylistchina最新规则

K3源官改修改方法：

将root/adb_mon.sh和

root/adbcmd.sh中能找到的以下网址替换成新的

替换前的

https://kprule.com/koolproxy.txt

https://kprule.com/kp.dat

https://kprule.com/daily.txt



替换成的网址

https://github.com/jhsvip/KoolProxy_Ruls/raw/main/koolproxy.txt

https://github.com/jhsvip/KoolProxy_Ruls/raw/main/kp.dat

https://github.com/jhsvip/KoolProxy_Ruls/raw/main/daily.txt


更新主程序至3.8.5方法
下载并拷贝Koolproxy文件至 /Root/Kool/

AdGuardHome 规则：

https://ghproxy.com/https://github.com/jhsvip/KoolProxy_Ruls/blob/main/ad.txt

https://ghproxy.com/https://github.com/jhsvip/KoolProxy_Ruls/blob/main/userAD.txt

白名单:
https://ghproxy.com/https://github.com/jhsvip/KoolProxy_Ruls/blob/main/white.txt

欢迎大家补充规则


更新ADG版本方法：


下载官方对应的版本https://github.com/AdguardTeam/AdGuardHome/releases

我的是MTK7621/MTK7620处理器 选择 AdGuardHome_linux_mipsle_softfloat.tar.gz 这个版本下载 解压缩后使用winscp把路由器的AdGuardHome文件替换即可
