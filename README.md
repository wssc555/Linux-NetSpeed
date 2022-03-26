# Linux-NetSpeed
本脚本已不更新，推荐使用5.5以上内核自带的bbr速度最佳
- https://roov.org/2020/03/bbr-bbrplus-bbr2/
- 推荐使用该脚本：bash <(curl -Lso- https://git.io/kernel.sh)
```
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh"
chmod +x tcp.sh
./tcp.sh
```
由于raw.githubusercontent.com访问较慢，先将tcp.sh里面的地址换成raw.sevencdn.com更换完内核之后，再换回raw.githubusercontent.com启用加速模块
