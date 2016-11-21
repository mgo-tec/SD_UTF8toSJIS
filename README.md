# This is the Arduino IDE & SD card library using the UTF8_to_Shift_JIS conversion table for the ESP8266.

これはESP-WROOM-02(ESP8266)の Arduino IDE ライブラリです。  
Version 1.2  
SPI接続のSDカードから読み込むためのものです。  
UTF8 to Shift_JIS 変換テーブルファイル "Utf8Sjis.tbl" を予めSDカードにコピーしておく必要があります。  
UTF-8コードのString文字列をShift_JIS文字列コードに変換できます。  
変換テーブルファイルURL--> https://github.com/mgo-tec/UTF8_to_Shift_JIS  
  
JIS第一水準、第二水準、１３区、半角カナが変換可能  
  
【更新履歴】  
(1.2)  
UTF-8の２バイト文字(C2A2～D191)を変換できるように修正しました。  
それと、計算を少々高速化しました。

(1.0.1)  
whileループ内でyield()を追加しただけです。  
  
参照ブログ https://www.mgo-tec.com  
  
The MIT license  
