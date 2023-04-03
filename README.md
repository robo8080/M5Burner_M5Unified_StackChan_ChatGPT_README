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
例えば、次のように指定します。<br>

http://192.168.11.20/chat?voice=4&text=こんにちは<br>


* ブラウザで"http://xxxx.xxxx.xxxx.xxxx/role"にアクセスすると、ロールを設定できます。<br>
(xxxx.xxxx.xxxx.xxxxはAIスタックチャンの起動時に表示されるIPアドレスです。)<br>
テキストエリアに何も入力せずに送信すると、以前に設定されたロールが削除されます。<br>
<br>
ロール情報は自動的にspiffsに保存されます。<br>
<br>

* AIスタックチャンの表情を会話内容に合わせて変更できます。<br>
ロール設定で以下の２行をそのまま入力してください。<br><br>
(Happy)のように、括弧で囲んで感情の種類を表し、返答の先頭に付けてください。<br>
感情の種類には、Neutral、Happy、Sleepy、Doubt、Sad、Angryがあります。<br>
<br>
他にもロールを設定する際は、これらの2行を最後にしてください。<br>
<br>

以上が、AIスタックチャンの使い方になります。<br><br>
### 注意点として、ファームを書き込み後には再度SDからAPIキーを設定することを忘れないようにしてください。 ###
<br><br>


