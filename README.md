# for-driver

GPIO25に接続されたLEDを点灯させるデバイスドライバです。

make
sudo insmod myled.ko
sudo chmod 666 /dev/myled0

と入力して利用してください。

echo 1 > /dev/myled0　と打つと激しく点滅します。
echo 1 > /dev/myled0　と打つと若干ゆっくり点滅します。
