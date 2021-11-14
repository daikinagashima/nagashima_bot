# LineBot を GAS で作成

## ボット作成

- linedevelopers からチャネルを作成
- GoogleDrive で GAS(Google Apps Script)を作成
- GCP でプロジェクトを作成
- GCP の API とサービスから OAuth 同意画面をクリック
- 流れに従って保存する
- GCP トップページにプロジェクト番号が記載されているので、番号をコピーする
- GAS に戻り、タブのリソースから CloudPlatform プロジェクトをクリック
- 先ほどの番号をペーストしてプロジェクトを設定をクリック
-

### 編集したコードをデプロイする

_AppsScript_ の上部にある*デプロイボタン*から新しいデプロイを選択。
設定を決めて(特になければデフォルトのままで OK)デプロイボタンを押下。
中央にあるウェブアプリの URL をコピーする。

[linedevelopers](https://script.google.com/macros/s/AKfycbx1Vl8iXH3OPm6xmIKpmBAeG_JoGATAzH7Xqq4aUQoFUTXdPnOH4WQANsItC6YrBgyITg/exec)を開く
サイドバーにある Admin からプロバイダーを指定し、チャネルを選択。
Messaging API 設定から Webhook 設定の編集ボタンを押下し、先ほどコピーした URL を貼り付ける。

編集後、念のため検証ボタンを押下し、GAS と連携されていることを確認する。
OK と出てれば完了。

※markdown のプレビューは ctrl+k の後に v を入力
