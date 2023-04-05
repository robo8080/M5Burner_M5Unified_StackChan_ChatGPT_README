# M5Burner_M5Unified_StackChan_ChatGPT_README
M5Burner版M5Unified_StackChan_ChatGPTのREADMEです。

M5Burnerに、テスト版の「AIスタックチャン」をアップロードしました。<br>
<br>

### 使い方 ###

* SDカードのルートに以下の2つのファイルを作成しておくと、使用できるようになります。<br>

1. wifi.txtファイル：ファイル名は"wifi.txt"で、中身は次の通りです。<br>
YOUR_WIFI_SSID<br>
YOUR_WIFI_PASS<br>

2. apikey.txtファイル：ファイル名は"apikey.txt"で、中身は次の通りです。<br>
YOUR_OPENAI_APIKEY<br>
YOUR_VOICETEXT_APIKEY<br>

* もしM5Stackが以前にWifiに接続していた場合、SDカードが必要なく自動的にWifiに接続されます。<br>
この場合、ブラウザで"http://XXX.XXX.XXX.XXX/apikey"にアクセスし、APIキーを設定できます。<br>
(xxxx.xxxx.xxxx.xxxxはAIスタックチャンの起動時に表示されるIPアドレスです。)<br>

* 声の変更には、voiceパラメータを指定できます。<br>
値は0〜4の範囲で指定できます。<br>
例えば、次のように指定します。<br><br>
http://192.168.11.20/chat?voice=4&text=こんにちは<br>
<br>

* ブラウザで"http://xxxx.xxxx.xxxx.xxxx/role"にアクセスすると、ロールを設定できます。<br>
(xxxx.xxxx.xxxx.xxxxはAIスタックチャンの起動時に表示されるIPアドレスです。)<br>
テキストエリアに何も入力せずに送信すると、以前に設定されたロールが削除されます。<br><br>
ロール情報は自動的にspiffsに保存されます。<br>
<br>

* ブラウザで"http://xxxx.xxxx.xxxx.xxxx/role_get"にアクセスすると、現在設定しているロールを取得できます。<br>

* AIスタックチャンの表情を会話内容に合わせて変更できます。<br>
ロール設定で以下の２行をそのまま入力してください。<br><br>
(Happy)のように、必ず括弧で囲んで感情の種類を表し、返答の先頭に付けてください。<br>
感情の種類には、Neutral、Happy、Sleepy、Doubt、Sad、Angryがあります。<br><br>
他にもロールを設定する際は、これらの2行を最後にしてください。<br>
出来ればこの2行のみでやってみてください。<br>
ロールを増やすと失敗しやすくなります。<br>
<br>

* 独り言モードを追加しました。ランダムな時間間隔で、ランダムに喋ります。<br>
感情表現機能と組み合わせると楽しいです。<br>
ボタンAで独り言モードをON/OFFできます。<br>
独り言モードでも従来通りスマホから会話できます。<br>
<br>

以上が、AIスタックチャンの使い方になります。<br><br>
### 注意点として、ファームを書き込み後には再度SDからAPIキーを設定することを忘れないようにしてください。 ###
<br>

---

### ChatGPTのAPIキー取得の参考リンク ###

* [ChatGPT API利用方法の簡単解説](https://qiita.com/mikito/items/b69f38c54b362c20e9e6/ "Title")<br>

### VoiceText Wev API api キーのキー取得のリンク ###

* APIキーは、[ここ](https://cloud.voicetext.jp/webapi/ "Title")の「無料利用登録」から申請すれば、メールで送られて来ます。<br>


### ChatGPTのキャラクター設定の参考リンク ###

* [ChatGPTのAPIでキャラクター設定を試してみた](https://note.com/it_navi/n/nf5f702b36a75#8e42f887-fb07-4367-9f3f-ab7f119eb064/ "Title")<br>
<br><br>

