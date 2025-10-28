# Linux-NetSpeed
本脚本已不更新，推荐使用5.5以上内核自带的bbr速度最佳
- https://roov.org/2020/03/bbr-bbrplus-bbr2/
- 推荐使用该脚本：bash <(curl -Lso- https://git.io/kernel.sh)
- 国内由于网络问题使用这个命令: bash <(curl -Lso- https://get.2sb.org/https://git.io/kernel.sh)
```
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh"
chmod +x tcp.sh
./tcp.sh
```
