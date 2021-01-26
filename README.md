>**説明**
ただ赤いLEDを光らせるだけのデバイスドライバーです。
---
>**実行する方法**
・以下を入力する。

$ make

$sudo insnod myled.ko

$sudo chmod666 /dev/myled0

---
>**LEDを光らせる**

$ echo 1 > /dev/myled0

---
>**LEDを消灯させる**

$ echo 0 > /dev/myled0

---
>**ドライバを削除する**

$sudo rmmod myled
