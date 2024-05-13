# G13 Joystick Repair kit 製作風景

<br>
<br>

## １．基板製作

![](./G13RepairKit_images/Making/making_01.jpg)  

オリジナルの基板をリバースエンジニアリングして、同等の回路で基板を製作しております。  

設計はKiCadで行い、GerberデータをJLCPCBに送って中国・深圳にて基板を製造します。  
<br>

これまでに外形、部品位置、フットプリントなど何度かリビジョンアップされておりますが、回路的には同一なので、以前のrevでも問題なく動作すると思います。

<br>
<br>
<br>
<br>

## ２．部品の実装

<br>
<br>

### コンデンサのハンダ付け

![](./G13RepairKit_images/Making/making_02.jpg)

ミニホットプレートとペーストはんだでチップコンデンサをリフローはんだ付けします。  

小ロットの場合やリードタイプのコンデンサを使うときは手ハンダします。

<br>
<br>

### 脚のカット

![](./G13RepairKit_images/Making/making_03.jpg)

キット取り付け時の干渉を防ぐためにマイクロスイッチ、ジョイスティックの脚の一部をカットしておきます。

<br>
<br>

### マイクロスイッチのハンダ付け

![](./G13RepairKit_images/Making/making_04.jpg)

ジョイスティック下側のマイクロスイッチはボタン直押し構造にするためMOD位置にハンダ付けします。

<br>
<br>

![](./G13RepairKit_images/Making/making_05.jpg)

ジョイスティック横のマイクロスイッチをハンダ付けします。

<br>
<br>

### ピンヘッダのハンダ付け

![](./G13RepairKit_images/Making/making_06.jpg)

ピンヘッダをハンダ付けします。間隔が狭いのでルーペを使って慎重に作業します。  
ハンダ付けが適切であればハンダがピカッと光り富士山のような裾広がり形状になります。

<br>
<br>

### ジョイスティックのハンダ付け

![](./G13RepairKit_images/Making/making_07.jpg)

ジョイスティックをハンダ付けします。こちらも間隔が狭い個所があるのでルーペを使って作業します。  

<br>
<br>

### 基板クリーニング

![](./G13RepairKit_images/Making/making_08.jpg)

ハンダ付け個所がフラックスで汚れているのでフラックスクリーナーやIPAを使い洗浄します。  

<br>
<br>

### ハンダ付けチェック

![](./G13RepairKit_images/Making/making_09.jpg)

ルーペ、実体顕微鏡などでハンダ付け不良がないか目視確認します。  

<br>
<br>

### 実機で確認

![](./G13RepairKit_images/Making/making_10.jpg)

基板が再生産された場合やリビジョンアップ、使用部品を変更した際はG13に繋いで実機で動作確認します。  

<br>
<br>

## ３．３Dプリンター部品の作成

<br>
<br>

### ジョイスティックカバーの作成

![](./G13RepairKit_images/Making/making_11.jpg)

ジョイスティックカバーは仕上がりや精度を高めるために１つずつ印刷します。  
PETG素材を使い、約25分かけて出力します。  

<br>
<br>

![](./G13RepairKit_images/Making/making_12.jpg)

３Dプリンターの特性上、糸引きやバリが出る箇所があるので、細いタガネなどを使いカットします。  
特に軸穴は念入りに調整します。  

<br>
<br>

![](./G13RepairKit_images/Making/making_13.jpg)

サムパッドカバーは、全数を実際にジョイスティックに取り付けて検査しております。  

<br>
<br>

![](./G13RepairKit_images/Making/making_14.jpg)

サムパッドを印刷して、ジョイスティックカバーに圧入で取付けします。  

<br>
<br>

### スイッチ押し用ネジの作成

![](./G13RepairKit_images/Making/making_15.jpg)

M2タッピングビスの先端が尖っているので、ペアンで掴み、ダイヤモンドホイールで平らに成形します。  

<br>
<br>

![](./G13RepairKit_images/Making/making_16.jpg)

3Dプリンターで製作したスリーブをビスに取り付けます。  
