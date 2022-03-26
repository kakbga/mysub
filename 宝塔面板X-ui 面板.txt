
ContOS 7



##安装bbrplus加速##


yum -y install wget    #ContOS 安装 wget


yum -y install curl    #ContOS 安装 curl


wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

##查看开启状态##

sysctl -p

##安装宝塔面板##
Centos全新安装命令：根据系统执行框内命令开始安装（大约2分钟完成面板安装）升级后可能需要重启面板

yum install -y wget && wget -O install.sh http://v7.hostcli.com/install/install_6.0.sh && sh install.sh

安装 & 升级 X-ui 面板
安装及升级的一键代码

bash <(curl -Ls https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh)
