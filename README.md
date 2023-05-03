## キットに同梱されているもの

|部品|個数|備考|
|:--|:--|:--|
|PCB|1|リードタイプと表面実装のダイオードに対応。|
|ダイオード|35||
|m2ネジ(14mm)|12||
|m2ナット|12||
|リセットスイッチ|1||
|滑り止めシール|6||

### 別途で用意するもの
|部品|個数|備考|
|:--|:--|:--|
|[アクリル板ケース](https://shop.yushakobo.jp/products/keyboard_acrylic_plate?variant=46424945328359)|1|遊舎工房にてお好みのカラーのTightwriterのケースを発注ください。キースイッチプレート、積層プレート、ボトムプレートでケースを組み立てます。|
|キースイッチ|35|Cherry MX互換|
|キーキャップ|35||
|Pro Micro|1||
|USBケーブル|1|Pro MicroとPCを接続します。|
|コンスルー|2|無くても組み立ては可能ですが、難易度がかなり高くなります。また失敗をしたときのリカバリーに膨大な手間がかかります。自作キーボードの組み立てに慣れた方以外は、コンスルーを使用することを強く推奨します。|
|キースイッチソケット|35|無くても組み立ては可能です。取り付けるとキースイッチを交換しやすくなるのと、組み立ての失敗を防ぎやすくなります。|

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

ダイオードはスルーホール型を用います。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2947.jpg?raw=true" width = "600px" />

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

**手順が難しく、やり直しには手間がかかるため、組み立てに慣れていない方にはコンスルーの使用を強く推奨致します。コンスルーを使用しなかった場合はサポート対象外となる場合がございますのでご了承ください。**

コンスルー(ピンヘッダ)は回路がある側とは逆に足が来るように、取り付けます。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3023.jpg?raw=true" width = "600px" />

Pro Microを取り付けます。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3025.jpg?raw=true" width = "600px" />

### 5. ファームウェアの書き込み

キースイッチを取り付ける前に、ダイオードが正常に取り付けられているかを確認すると作業の手戻りが少なくなります。
Pro Microにファームウェアを書き込みます。QMK Firmwareでビルドされる方は[こちらのプルリクエスト](https://github.com/qmk/qmk_firmware/pull/20136)からソースコードを取得できます。  
VIAに対応したファームウェアもご用意しており、WebブラウザからRemapを開いてファームウェアの書き込みとキーマップの変更が可能です。
[こちら](https://remap-keys.app/catalog/qY2AY5eBIwnzIcmLRJUD/firmware)からファームウェアの書き込みができます。  
<img src = "https://user-images.githubusercontent.com/4215759/235832632-778d0d9b-cfde-4d2d-b054-8e549eca977c.png?raw=true" width = "600px" />

VIAに対応したファームウェアを書き込んだ状態でRemapを開き、「Test Matrix Mode」を実行すると、キーの入力確認画面に遷移します。  
<img width="600" alt="image" src="https://user-images.githubusercontent.com/4215759/235834545-46f360c1-6e2d-4f08-9e54-16814cc4e3a3.png">

「Test Matrix Mode」でTightwriterのキーを押すと押されたキーが点灯します。  
<img width="600" alt="image" src="https://user-images.githubusercontent.com/4215759/235834717-30d272d7-80c7-43d3-a517-f3f501459777.png">

キースイッチのハンダ付け箇所を導通させると、キースイッチを付けずとも入力の確認が可能です。  
ピンセットなどを用いるのが良いかと思われます。  
<img src = "https://raw.githubusercontent.com/takashicompany/ergomirage/master/images/build/IMG_4481.jpg?raw=true" width = "600px" />
(画像は別キーボードです)

### 6. LEDの取り付け

LED(WS2812B)は組み立て後でも取り付けが可能です。  
LEDは以下の順番に取り付けます。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2946_led.jpg?raw=true" width = "600px" />

### 7. キースイッチの取り付け

自作キーボードの組み立て経験が浅い方はa.をオススメ致します。

#### a. キースイッチソケットを利用する場合

キースイッチソケットをキースイッチの固定に利用することでキースイッチの交換が用意になります。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2966.jpg?raw=true" width = "600px" />

キースイッチソケットはMX用の印刷がされた箇所に差し込みます。
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2969.jpg?raw=true" width = "600px" />

キースイッチソケットのハンダ付け箇所の片方に事前にハンダを溶かして載せておきます。(予備ハンダ)  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2970.jpg?raw=true" width = "600px" />

ピンセットでキースイッチソケットを持ちながら予備ハンダをハンダごてで溶かしながらキースイッチソケットの片側をハンダ付けします。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2971.jpg?raw=true" width = "600px" />

もう片側もハンダ付けをして取り付けが完了です。
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2972.jpg?raw=true" width = "600px" />

尚、Pro Microの箇所のキースイッチのみ、Choc v1のキースイッチソケットを取り付けることはできませんのでご注意ください。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_2974.jpg?raw=true" width = "600px" />

#### b. キースイッチソケットを使用せず直接PCBする

後述のキースイッチプレートにキースイッチをはめ込み、PCBにキースイッチの足を通しハンダ付けをします。

### 8. スタビライザーの取り付け

スタビライザーは、長いキーを安定させる・キーのどこを押しても押下できるようにするパーツです。  
なくてもキーボードとして動作は可能です。  
スタビライザーをご利用される場合は、2u用が二つと6.25u用がご用意頂くとよろしいかと思います。
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3030.jpg?raw=true" width = "600px" />

スタビライザーはPCBに挿し込むことで装着が可能です。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_.jpg?raw=true" width = "600px" />

### 8. ケースの組み立て

ケースを組み立てます。  
下の写真は上から

- キースイッチプレート
- 積層プレート(左上、左下、右上、右下)
- ボトムプレート

となります。

積層プレートは各種類が2枚ずつ必要となります。(合計8枚)  
また、遊舎工房でケースを発注された場合はボトムプレートが一部くり抜かれたデザインとなっています。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3029.jpg?raw=true" width = "600px" />

スイッチプレートと積層プレート、ボトムプレートをPCBと重ね合わせます。  
この際にキースイッチを数個程度スイッチプレートに事前に挿しておき、PCBのソケットに挿すとPCBとスイッチプレートを仮止めできます。
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3032.jpg?raw=true" width = "600px" />

各種プレートはネジとナットで固定します。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3034.jpg?raw=true" width = "600px" />

ネジはキーボードの表側から通します。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3036.jpg?raw=true" width = "600px" />

裏面から飛び出たネジの足をナットで固定します。このときキーボードを逆さまにするとネジが取れてしまうことがありますので、ネジをマスキングテープなどで仮止めしておくと、作業がスムーズに進むかと思います。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3037.jpg?raw=true" width = "600px" />

ケースが固定できたらキースイッチを差し込みます。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3038.jpg?raw=true" width = "600px" />

### 9. ゴム足シールの取り付け

ゴム足シールをボトムプレートに貼り付けます。  
<img src = "https://github.com/takashicompany/minidivide/raw/master/images/build/IMG_3748.jpg?raw=true" width = "600px" />

以下は取り付け例です。ご自身の打鍵スタイルにあった位置を探してみてください。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3037.jpg?raw=true" width = "600px" />

### 10. キースイッチにキーキャップを挿し込む

キースイッチにキーキャップを挿し込んで完成です。  
<img src = "https://github.com/takashicompany/tightwriter/blob/master/images/build/IMG_3041.jpg?raw=true" width = "600px" />

