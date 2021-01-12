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
$cd ~/catkin_ws/sec
$git clone https://github.com/Kentotomi/Robosys_ros.git
$cd ..
$catkin_make
$cd scripts/
$chmod 755 sender.py receiver.py
```
ターミナル1
```
roscore
```
ターミナル2
```
rosrun Robosys_ros sender.py
```
ターミナル3
```
rosrun Robosys_ros receiver.py
```
