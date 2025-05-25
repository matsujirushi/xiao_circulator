無印良品 360度首振り機能付きサーキュレーターをSeeed Studio XIAOで制御してみようプロジェクト。

# 改造するサーキュレーター

無印良品 360度首振り機能付きサーキュレーター6畳ホワイト MJ-OCF06

<img src="media/2.jpg" width="300">
<img src="media/1.jpg" width="300">
<img src="media/14.jpg" width="300">

ガードを外した状態

<img src="media/3.jpg" width="300">

## 上部の中身

<img src="media/4.jpg" width="300">

<img src="media/5.jpg" width="300">

* MST35 12V DC 0041/241030C NINGBO MINGSHENG
* ステッピングモーター

## 下部の中身

<img src="media/6.jpg" width="300">

<img src="media/8.jpg" width="300">
<img src="media/9.jpg" width="300">

<img src="media/12.jpg" width="150">
<img src="media/13.jpg" width="150">
<img src="media/10.jpg" width="150">
<img src="media/11.jpg" width="150">
<img src="media/7.jpg" width="150">

* SN8F570320ASG

* ULN2003G 7ch darlington sink driver

    <img src="media/15.png" width="150">

* AiP650EO 2-line Serial Interface/LED Driver with Keyboard

    <img src="media/16.png" width="150">

## 基板の解析

<img src="media/17.jpg" width="300">

### U1

|Pin|Note|
|:--|:--|
|1|GND|
|2|V-MOTOR 2-Orange|
|3|V-MOTOR 3-Yellow|
|4|V-MOTOR 4-Purple|
|5|V-MOTOR 5-Blue|
|6|H-MOTOR 2-Orange|
|7|H-MOTOR 3-Yellow|
|8|H-MOTOR 4-Purple|
|9|H-MOTOR 5-Blue|
|10|LED Driver CLK|
|11|SW ON/OFF|
|12|SW SPEED|
|13|SW RL|
|14|SW UD|
|15|SW TIME|
|16|LED Driver DIO|
|17|FAN-MOTOR H-Red|
|18|FAN-MOTOR M-White|
|19|FAN-MOTOR L-Blue|
|20|+5V|
