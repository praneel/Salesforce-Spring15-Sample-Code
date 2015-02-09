# Salesforce Spring'15 Sample Code
Spring'15 Pre-Releaseの環境で新機能を試してみました。  
  
## - Apex -  
### ApexMapDemo
<apex:map>のデモ画面です。リリースノートに記載されているサンプルコードを動かしてみました。  
URLパラメータで取引先IDを渡す必要があります。  

<img src="http://f.st-hatena.com/images/fotolife/t/tyoshikawa1106/20150204/20150204070147.png" width="500px;" />

### AccountMapView
<apex:map>のデモ画面です。取引先の住所情報を使ってマーカー表示しています。  
一度に表示できるマーカーは10個までとなるみたいです。

<img src="http://f.st-hatena.com/images/fotolife/t/tyoshikawa1106/20150205/20150205025331.png" width="500px;" />

### AddressAndLocationDemo
Apex を使用した住所複合項目および地理位置情報複合項目へのアクセス機能のデモです。  
カスタム項目『MyLocation__c』が必要になります。  

<img src="http://f.st-hatena.com/images/fotolife/t/tyoshikawa1106/20150205/20150205024213.png" width="500px;" />

<img src="http://f.st-hatena.com/images/fotolife/t/tyoshikawa1106/20150205/20150205024926.png" width="500px;" />

### CommonTestSetup
@testSetupのデモクラスです。

<img src="http://f.st-hatena.com/images/fotolife/t/tyoshikawa1106/20150205/20150205030237.png" width="500px;" />

### Chatter Message Trigger
ユーザプロファイルにある『Chatter メッセージの管理』を有効にすることでChatterMessageトリガーを作成できるようになります。NGワードを判定したり、送信相手にToDoを作成するなどの使い方ができそうです。

<img src="http://f.st-hatena.com/images/fotolife/t/tyoshikawa1106/20150207/20150207173750.png" width="500px" />

### DMLOptionsDemo
ApexのDMLOptions Classを利用した重複チェックです。

<img src="http://f.st-hatena.com/images/fotolife/t/tyoshikawa1106/20150209/20150209215329.png" width="500px" />

次の一致ルールを作成して確認しています。

<img src="http://f.st-hatena.com/images/fotolife/t/tyoshikawa1106/20150209/20150209215659.png" width="500px" />

重複ルールは次のような感じです。

<img src="http://f.st-hatena.com/images/fotolife/t/tyoshikawa1106/20150209/20150209220227.png" width="500px" />

## Test Class
今回用意したサンプルコードはテストクラスで簡単に動作確認してあります。

<img src="http://f.st-hatena.com/images/fotolife/t/tyoshikawa1106/20150209/20150209221120.png" width="500px" />


## - Lightning Component -
### Hello World
Lightningの開発では名前空間プレフィックスが不要になり、apexと同じように『c:』で宣言できるようになりました。

<img src="http://f.st-hatena.com/images/fotolife/t/tyoshikawa1106/20150205/20150205050844.png" width="500px;" />
