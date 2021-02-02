>**ロボットシステム学_課題１**
---
>**概要**

1を入力するとLEDが点灯、0を入力すると消灯するプログラム。

---
>**動作環境**

OSはUbuntu 18.04

---
>**使用したもの**

・Raspberry Pi4

・ブレッドボード

・LED ×１

・抵抗器(100Ω) ×１

・ジャンパー線　×４

---

>**実行手順**

順番に以下のコマンドを入力する。

$git clone https://github.com/hyotakiguchi/robosys_homework1.git

$cd myled

$make

$sudo insmod myled.ko

$sudo chmod 666 /dev/myled0

---
>**LEDを点灯させる**

$ echo 1 > /dev/myled0

---
>**LEDを消灯させる**

$ echo 0 > /dev/myled0

---

>**もう実行しないなら**

$sudo rmmod myled

---
>**実際にLチカさせている様子(YouTube)**

https://youtu.be/AULwmZY3fQk

>**ライセンス**

このリポジトリには以下のライセンスが付与されています。

GNU General Public License v3.0
