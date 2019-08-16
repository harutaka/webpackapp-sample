# webpackapp-sample
webpackを使ってes6とsassをビルドする簡単なサンプルである。

## 必要な環境とバージョン
* Nodejs
  * 10.16.1

## 使い方
`npm run build`を実行すると、srcディレクトリの中身を変換し、  
成果物をdistディレクトリに配置する。

`npm start`を実行すると、webpack-dev-serverの機能を使用し、  
webpackでローカルサーバーを起動し、  
変更時にブラウザをリロードする形で開始する

`npm run watch`を実行すると、ファイルの変更点の再ビルドを実行する。  

