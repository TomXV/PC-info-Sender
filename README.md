# ここには来てはいけない、引き返したほうがいい。

![ECLFKc1UYAAhDnI](https://github.com/user-attachments/assets/8b302604-87af-43c3-a265-0381bf214451)

このリポジトリは、ユーザーのPC情報や位置情報を収集し、指定されたエンドポイントに送信するWebページです。  
エンジニアの暇つぶしとして作成されました。

かなり、アングラなコードになってます。  
世の中にはこんな危険なサイトがあるという教育目的で説明に使ってみてはいかがでしょうか？

このコードで、悪用なんてしようとしたらできちゃいますけど・・・あなたが光を得るか闇を得るかはあなた次第です。

JavaScriptができるなら、改良をくわえてもいいですよ。

## 動作概要
- ページを訪れると、位置情報の送信許可を求めるダイアログが表示されます。
- ユーザーが「許可する」ボタンをクリックすると、ブラウザの位置情報APIを使用して現在の位置情報を取得します。
- ユーザーが位置情報の共有を拒否した場合や、位置情報の取得が失敗した場合は、IPアドレスベースの位置情報を取得します。
- 取得した位置情報およびその他のPC情報（ユーザーエージェント、言語、プラットフォーム、画面の解像度など）を指定されたエンドポイントにPOSTリクエストとして送信します。
- 送信された情報はページ内に表示されます。

## 最後に
どんなものなのか知りたい場合は [このサイト](https://tomxv.github.io/PC-info-Sender/) にアクセスしてみてください。しかし、絶対におすすめしません。最悪身元がバレる可能性が高いので、家の近くや職場の近くでは開かないようにしてくださいね。
