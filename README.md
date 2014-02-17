# RealPageDown
## 
This document is made by [gitfab](http://gitfab.org)
---
#概要
Firefoxからarduino.jsを通してArduinoとサーボモータを制御するサンプルです。

Firefoxのコンテクストメニューから、「Real PageDown」を選択するとサーボモータが動いて、「↓」キーを押します。

<iframe src="//www.youtube.com/embed/2FNyW4zn8Fg" width="400" frameborder="0" height="300"></iframe>
---
#準備
以下のものを準備してください。

###ソフトウェア

1. [Firefox](http://www.mozilla.jp/firefox/)

###ハードウェア

1. Arduino （Unoが扱いやすいです）
1. ジャンパワイヤ
1. [サーボモータ](http://www.ministudio.co.jp/Cgi-bin/Order-JP/DetailJp.asp?GoodsNum=54)
1. ペン
1. はがしやすいテープ

---
#ハードウェア

以下の図のように配線します。

![スクリーンショット 2014-02-14 13.23.37.png](https://raw.github.com/oshimaryo/RealPageDown/master/)

以下は回路図のFritzingファイルです。（上の図と中身は同じです。）

[fullColorLED-CDSCell.fzz](https://raw.github.com/oshimaryo/CDSCell-and-FullColorLED-Sample/master/gitfa

---
#ソフトウェア

###インストール
ソースコードは[githubレポジトリ](https://github.com/oshimaryo/real-page-down)にアップされています。

画面右下側にある「Download ZIP」ボタンをクリックして、デスクトップにダウンロード、解凍します。

解凍したディレクトリ内にある
「real_page_down.xpi」をFirefoxにドラッグアンドドロップします。

###動作確認
Firefoxを立ち上げて、任意のページにテキストをハイライトし、右クリックしたところに「Real PageDown」というメニューが追加されたことを確認します。
それをクリックし、サーボモータが動けばOKです。
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
