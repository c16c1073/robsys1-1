# robsys_kadai_1
# ロボットシステム学課題１
## 概要
LEDを1を入力して点灯，0を入力して消灯する．
## デバイスドライバの作成
```
$ git clone https://github.com/ryuichiueda/raspberry_pi_kernel_build_scripts.git
$ cd raspberry_pi_kernel_build_scripts
$ sudo ./karnel_build_and_install_for_pi2_pi3.bash
$ sudo reboot
```
## 動画URL
https://youtu.be/A2Mm7umCyK0

## 使用方法
```
$ git clone https://github.com/yutaroiida/robsys1.git
$ cd robsys1
$ make
$ sudo insmod myled.ko
$ sudo chmod 666 /dev/myled0
```
LEDを点灯させる．
`$ echo 1 > /dev/myled0`
LEDを消灯させる．
`$ echo 1 > /dev/myled0`
