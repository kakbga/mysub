*****

# 脚本合集

## 测速脚本：

```shell
bash <(curl -Lso- https://od.okjason.com/5-Linux/scripts/speedtest.sh)
```


## DDNS:
```shell
wget -qO- https://od.okjason.com/5-Linux/scripts/ddns.sh | bash
```

## RHEL IPv6:
```shell
# 7.0+
yum install wget -y && wget -O /etc/sysconfig/network-scripts/ifcfg-eth0 https://od.okjason.com/5-Linux/scripts/ifcfg-eth0 && systemctl restart network

# 8.0+
yum install wget -y && wget -O /etc/sysconfig/network-scripts/ifcfg-eth0 https://od.okjason.com/5-Linux/scripts/ifcfg-eth0 && nmcli c reload
```

## 奈飞解锁检测：
```shell
wget -qO- https://od.okjason.com/5-Linux/scripts/nf.sh | bash
```