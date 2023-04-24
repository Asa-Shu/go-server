## Simple Go Web Server

簡単な Go 言語で書かれた Web サーバーです。この Web サーバーは、静的ファイルの提供、フォームデータの処理、およびシンプルなエンドポイントのルーティングを行います。



https://user-images.githubusercontent.com/64985323/234057105-5c946157-1ee4-41af-b545-fed8be1daade.mov



## 機能

静的ファイルの提供: ./static ディレクトリ内のファイルをホストします。

フォームデータの処理: /form エンドポイントに送信された POST リクエストのフォームデータを解析し、取得したデータをレスポンスに含めます。

シンプルなエンドポイントのルーティング: /hello エンドポイントへの GET リクエストに対して、"hello!"というメッセージを返します。

## 使い方

このリポジトリをクローンまたはダウンロードします。

`git clone https://github.com/Asa-Shu/go-server.git`

プロジェクトのディレクトリに移動します。
`cd simple-go-web-server`

サーバーを起動します。
`go run main.go`

Web ブラウザで http://localhost:8080 にアクセスして、静的ファイルが表示されることを確認します。

form.html のフォームを埋め /form エンドポイントに POST リクエストとして送信します。フォームデータが適切に処理されることを確認します。

Web ブラウザで http://localhost:8080/hello にアクセスして、"hello!"というメッセージが表示されることを確認します。

### 要件
Go 1.14 以降

### ライセンス
MIT License
