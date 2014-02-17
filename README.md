# RealPageDown
## 
This document is made by [gitfab](http://gitfab.org)
---
#概要
Arduinoで照度センサ（CDS Cell）とフルカラーLEDを連携させるサンプルです。

照度センサをタッチセンサのように使い、フルカラーLEDの色を切り替えます。

フルカラーLEDはPWM点灯しています。

<iframe src="//www.youtube.com/embed/2FNyW4zn8Fg" width="400" frameborder="0" height="300"></iframe>
---
#準備
以下のものを準備してください。

###ソフトウェア

1. [Arduino IDE](http://arduino.cc)

###ハードウェア

1. Arduino （Unoが扱いやすいです）
1. ブレッドボード
1. [フルカラーLED](http://akizukidenshi.com/catalog/g/gI-02476/)
1. [CDSセル](http://akizukidenshi.com/catalog/g/gI-00110/)
1. 抵抗：330Ω x4
1. ジャンパワイヤ

簡単のために330Ωの抵抗に統一しています。
「参考」の「回路について」のリンクを参考にすることで、より正確な回路が作れます。

---
#ハードウェア

以下の図のように配線します。

![スクリーンショット 2013-12-13 17.48.59.png](https://raw.github.com/oshimaryo/CDSCell-and-FullColorLED/master/gitfab/resources/スクリーンショット-2013-12-13-17.48.59.png)

以下は回路図のFritzingファイルです。（上の図と中身は同じです。）

[fullColorLED-CDSCell.fzz](https://raw.github.com/oshimaryo/CDSCell-and-FullColorLED-Sample/master/gitfa

---
#ソフトウェア
ソースコードは[githubレポジトリ](https://github.com/oshimaryo/FullColorLED_and_illuminanceSensor)にアップされています。

画面右下側にある「Download ZIP」ボタンをクリックして、デスクトップにダウンロードします。

![スクリーンショット 2013-12-13 17.20.54.png](https://raw.github.com/oshimaryo/CDSCell-and-FullColorLED/master/gitfab/resources/スクリーンショット-2013-12-13-17.20.54.png)

ダウンロードしたz


---
#完成図



![IMG_6442.JPG](https://raw.github.com/oshimaryo/RealPageDown/master/)
---
# 参考

### 回路図の作り方

1. [Fritzing](http://fritzing.org/download/)

### Arduinoとarduino.js

1. [Arduino](http://arduino.cc/)
1. [arduino.js](http://mecha-mozilla.org/projects/arduino.js/)
---
