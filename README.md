# ProMicroCH552

<img src="https://github.com/akita11/ProMicroCH552/blob/main/ProMicroCH552.png" width="240px">

[WCH(南京沁恒微电子股份有限公司)](http://wch-ic.com/)の8ビットマイコン[CH552](http://wch-ic.com/products/CH552.html)を使った、ProMicro型のマイコンボードです。
主な特徴は以下のとおりです。

- ProMicro型
- [ArduinoIDEなどでプログラム開発が可能](https://qiita.com/akita11/items/d7baed4ca3c06e292637)
- USBペリフェラル（キーボードやUSBメモリなど）として動作可能
- USB Type-Cコネクタ

またProMicroとは、以下のような違いがあります。
- 一部ピンの機能が異なる
- 一部未接続の端子がある
- リセット(RST)は正論理で、"1"でリセット
- +5V端子に、外部電源から+5Vを供給可能（内部にレギュレータはないので、+5Vを超える電圧は不可）


## ピン配置

<img src="https://github.com/akita11/ProMicroCH552/blob/main/ProMicroCH552_pin.png" width="720px">

<img src="https://github.com/akita11/ProMicroCH552/blob/main/ProMicroCH552_Back.png" width="240px">

基板上の"LED"（オレンジ）はP1.7で駆動できます。

# 訂正

基板上の2個のシルク表示が逆になっているロットがあります。正しくは、R4側が"LED"（オレンジ）、反対側が"POW"（緑、電源インジケータ）です。


## Author

Junichi Akita (@akita11) / akita@ifdl.jp






