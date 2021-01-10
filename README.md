# Robosys_ros
ロボット

# DEMO
## デモ動画
https://youtu.be/LuHbcHY41jg


# Features
sender.pyに入力されたテキストをreceiver.piで0.1秒ごとに受け取り，時間とともに表示する

# Requirement
## 環境
- OS: Ubuntu 20.04
- Ros Noetic

# Usage

```
$git clone https://github.com/Kentotomi/Robosys
$cd Robosys_devicedriver
$make
$sudo insmod myled.ko
$sudo chmod 666 /dev/myled0
$echo 1 > /dev/myled0 //点灯
$echo 0 > /dev/myled0 //消灯
sudo rmmod myled //削除
```
# License
"myled.c" is under [GNU General Public License](https://ja.wikipedia.org/wiki/GNU_General_Public_License)
