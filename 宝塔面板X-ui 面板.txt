##宝塔面板X-ui 面板###


##安装bbrplus加速##


yum -y install wget    #ContOS 安装 wget


yum -y install curl    #ContOS 安装 curl


wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

##查看开启状态##

sysctl -p

##安装宝塔面板##

Linux面板7.9.0安装脚本

使用 SSH 连接工具，如堡塔SSH终端连接到您的 Linux 服务器后，挂载磁盘，根据系统执行相应命令开始安装（大约2分钟完成面板安装）：

Centos安装脚本

yum install -y wget && wget -O install.sh http://download.bt.cn/install/install_6.0.sh && sh install.sh

Ubuntu/Deepin安装脚本

wget -O install.sh http://download.bt.cn/install/install-ubuntu_6.0.sh && sudo bash install.sh

Debian安装脚本

wget -O install.sh http://download.bt.cn/install/install-ubuntu_6.0.sh && bash install.sh

Fedora安装脚本

wget -O install.sh http://download.bt.cn/install/install_6.0.sh && bash install.sh

注意：必须为没装过其它环境如Apache/Nginx/php/MySQL的新系统,推荐使用centos 7.X的系统安装宝塔面板

##安装 & 升级 X-ui 面板##

bash <(curl -Ls https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh)





宝塔纯净版 7.6.0版本 [稳定版本/推荐]

Centos全新安装命令：根据系统执行框内命令开始安装（大约2分钟完成面板安装）升级后可能需要重启面板

yum install -y wget && wget -O install.sh http://v7.hostcli.com/install/install_6.0.sh && sh install.sh

Ubuntu/Deepin全新安装命令：

wget -O install.sh http://v7.hostcli.com/install/install-ubuntu_6.0.sh && sudo bash install.sh

Debian全新安装命令：

wget -O install.sh http://v7.hostcli.com/install/install-ubuntu_6.0.sh && bash install.sh

Fedora全新安装命令：

wget -O install.sh http://v7.hostcli.com/install/install_6.0.sh && bash install.sh

升级代码/修复面板：已经安装官方面板，执行下列命令升级到7.6.0纯净版：

curl http://v7.hostcli.com/install/update6.sh|bash

其他非官方版本含开心版、快乐版、纯净版等 7.4.5至7.6.0版本之间所有版本均可，执行下列命令升级到7.6.0纯净版：

curl http://v7.hostcli.com/install/update6.sh|bash

任意非官方版本还原到官方最新版：

curl http://download.bt.cn/install/update6.sh|bash


