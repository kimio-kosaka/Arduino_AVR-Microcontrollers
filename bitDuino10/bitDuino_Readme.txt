まりす(@maris_HY)氏の bitDuino ( http://100year.cocolog-nifty.com/blog/2014/08/arduino-f0f0.html )　
のファイル群(bitDuino_2014_09_09)をArduino IDE 1.6.13向けに再構成したものです。

arduino.cc の Arduino IDE 1.6.13用です。 arduino.orgのArduino IDには対応していません。


bitDuino_2014_09_09からの変更点

１．bitDuino10とbitDuino13に切り分けて，それぞれ独立のフォルダに収容した。

２．ファイル群のツリー構造を1.6.13向けに変更した。

３．board.txtを1.6.13向けに改編した。

４．platform.txtを追加した。
　　　　bitDuino10とbitDuino13のplatform.txtはavrdudeに引き渡すパラメータの定義が異なっています。
　　　　このため，bitDuino10とbitDuino13を別フォルダに切り分ける必要がありました，

