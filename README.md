## キットに同梱されているもの

|部品|個数|備考|
|:--|:--|:--|
|PCB|1|リードタイプと表面実装のダイオードに対応。|
|キースイッチプレート|1|MX互換キースイッチの場合は厚さ3mm、Kailh Choc v1キースイッチの場合は2mm厚を推奨。|
|積層サイドプレート|8||
|ボトムプレート|1||
|ダイオード|35||
|m2ネジ(14mm)|12||
|m2ナット|12||
|リセットスイッチ|1||
|滑り止めシール|6||

### 別途用意するもの
|部品|個数|備考|
|:--|:--|:--|
|キースイッチ|35|Cherry MX互換のもの or Kailh Choc v1|
|キーキャップ|35||
|Pro Micro|1||
|USBケーブル|1|Pro MicroとPCを接続します。|

### オプション
|部品|個数|備考|
|:--|:--|:--|
|コンスルー|2||
|キースイッチソケット|35||
|LED(WS2812B)|10|アンダーグロウライトとしてキーボードの底面を光らせることができます。|

### 1. PCBの表裏を確認する

表
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2943.jpg?raw=true" width = "600px" />

裏
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2946.jpg?raw=true" width = "600px" />

### 2. ダイオードの取り付け

ダイオード
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_.2947jpg?raw=true" width = "600px" />

ダイオードはPCB裏面から取り付けます。ダイオードの中央部のカソード(黒い線)がPCBの`▷|`の縦線の向きと同じになるように配置します。  
下図を例に上げると、ダイオードのカソードが右側に来るようにしています。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2950.jpg?raw=true" width = "600px" />

ダイオードが穴に入るように、足を折り曲げます。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2951.jpg?raw=true" width = "600px" />

ダイオードの足を穴に通します。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2952.jpg?raw=true" width = "600px" />

PCBの表面からダイオードの足が出ていることを確認します。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2953.jpg?raw=true" width = "600px" />

PCBの表面にダイオードの足をハンダ付けします。
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2954.jpg?raw=true" width = "600px" />

ハンダ付けが済むと以下のようになります。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2956.jpg?raw=true" width = "600px" />

ダイオードの足をニッパーで切ります。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2957.jpg?raw=true" width = "600px" />

### 3. リセットスイッチの取り付け

ファームウェア書き込み時等に利用するリセットスイッチを取り付けます。 
リセットスイッチはタクトスイッチを使用します。
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2975.jpg?raw=true" width = "600px" />

取り付け位置は基盤裏側の「RESET」の文字が書かれた箇所です。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2976.jpg?raw=true" width = "600px" />

タクトスイッチを穴に挿します。
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2977.jpg?raw=true" width = "600px" />

基盤表面にタクトスイッチの足が出ていることを確認します。  
足をハンダ付けして取り付け完了です。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2978.jpg?raw=true" width = "600px" />

### 4. Pro Microの取り付け

Pro Microは基盤裏側に取り付けます。取り付けにはピンヘッダかコンスルーを用います。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3024.jpg?raw=true" width = "600px" />  

なお、コンスルーを用いずピンヘッダで取り付ける場合は

1. ピンヘッダをPCBに取り付ける(ピンヘッダの足をPCB表側からハンダ付け)
1. キースイッチやMXソケットをトッププレートと一緒にハンダ付けする
1. Pro Microを取りける

といった手順となります。

** 手順が難しく、やり直しには手間がかかるため、組み立てに慣れていない方にはオススメしません。**

コンスルー(ピンヘッダ)は回路がある側とは逆に足が来るように、取り付けます。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3023.jpg?raw=true" width = "600px" />

Pro Microを取り付けます。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3025.jpg?raw=true" width = "600px" />

### 5. ファームウェアの書き込み

<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

### 6. LEDの取り付け

LED(WS2812B)は組み立て後でも取り付けが可能です。  
LEDは以下の順番に取り付けます。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2946_led.jpg?raw=true" width = "600px" />

### 7. キースイッチの取り付け

#### a. キースイッチソケットを利用する場合

キースイッチソケットをキースイッチの固定に利用することでキースイッチの交換が用意になります。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2966.jpg?raw=true" width = "600px" />

キースイッチ
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2969.jpg?raw=true" width = "600px" />
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />
