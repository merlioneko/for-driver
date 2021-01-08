# for-driver

## 概要

　GPIO25に接続されたLEDを点灯させるデバイスドライバです.


##環境設定
　OS:Ubuntu 20.04 LTS
　ハード:Raspberry Pi 4


## 使用方法

　以下に沿ってビルドしてください.

`$ make`

`$ sudo insmod myled.ko`

`$ sudo chmod 666 /dev/myled0`


　以下の様に入力する事で点灯します.
　数値によって点灯の激しさが異なります.


`$ echo 1 > /dev/myled0`

`$ echo 0 > /dev/myled0`


## ライセンス

 COPYINGに準じます。
