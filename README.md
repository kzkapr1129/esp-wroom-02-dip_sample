# ESP-wroom-02
## プログラムの書き込み手順
0. electrical_diagram.pngから以下の通り配線を変更する
- IO0: 10kΩでグランド  
- IO2: 10kΩで3.3V
1. arduino IDEをインストールする  
2. IDEを起動する  
3. メニュー → 環境設定 → 追加のボードマネージャのURLに以下を設定する  
http://arduino.esp8266.com/stable/package_esp8266com_index.json
4. 環境設定を閉じる  
5. メニュー → ボード → Generic ESP8266 Module を選択する
6. プログラムを書く (connect_to_wifi_sample.txt参照)
7. メニュー → スケッチ → マイコンボードに書き込む
