****

# arm64架构VPS DD包及脚本：

## CentOS7

sha256-adc3b0d4da250ce96aa370149c3e497ec9ec649324f8d29aba9688c935e973e7

```shell
# 挂载硬盘DD
gzip -dc ./CentOS7_arm64.img.gz | dd of=/dev/sdb bs=10M status=progress
# 本机不关机DD
yum/apt install wget -y
echo 1 > /proc/sys/kernel/sysrq
echo u > /proc/sysrq-trigger
wget -O - "https://od.okjason.com/5-Linux/arm64_DD/CentOS7_arm64.img.gz" -q | gzip -dc |  dd of=/dev/sda bs=10M status=progress
echo 'b' > /proc/sysrq-trigger
```
用户名： root
密码： okjason.com


## AlmaLinux8
sha256-4c44d7d95c2ef30e5d05b28e327b7e7c8283606eb4314e2d1f3cec98e4de7fd6
```shell
# 挂载硬盘DD
gzip -dc ./AlmaLinux8_arm64.img.gz | dd of=/dev/sdb bs=10M status=progress
# 本机不关机DD
yum/apt install wget -y
echo 1 > /proc/sys/kernel/sysrq
echo u > /proc/sysrq-trigger
wget -O - "https://od.okjason.com/5-Linux/arm64_DD/AlmaLinux8_arm64.img.gz" -q | gzip -dc |  dd of=/dev/sda bs=10M status=progress
echo 'b' > /proc/sysrq-trigger
```
用户名： root
密码： okjason.com

## Debian10
sha256-59ce7af4737c3003f169b39dbde9abaf27b129c8ea2bf33d79d0a74e2ce348b9
```shell
# 挂载硬盘DD
gzip -dc ./Debian10_arm64.img.gz | dd of=/dev/sdb bs=10M status=progress
# 本机不关机DD
yum/apt install wget -y
echo 1 > /proc/sys/kernel/sysrq
echo u > /proc/sysrq-trigger
wget -O - "https://od.okjason.com/5-Linux/arm64_DD/Debian10_arm64.img.gz" -q | gzip -dc |  dd of=/dev/sda bs=10M status=progress
echo 'b' > /proc/sysrq-trigger
```
用户名： root
密码： okjason.com