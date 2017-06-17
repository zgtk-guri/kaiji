# 確率統計録カイジ 運営システム
確率統計録カイジは、NITTCの文化祭で実施しているアトラクションである。
このアトラクションは、主にタブレット端末を用いたシステムによって運営されている。

## 開発者
* @zgtk-guri
* @kiotaku
* amedama
* ...and 2 anonymous developers

## 写真
* [2016年度の写真](./photos2016/photos2016.md)

## リポジトリ
### [kaiji-protoc](https://github.com/zgtk-guri/kaiji-protoc) by @zgtk-guri
Grpcでの通信プロトコルの定義ファイル。
### [kaiji-android](https://github.com/zgtk-guri/kaiji-android) by @zgtk-guri
Androidタブレット用のゲーム進行クライアント
### kaiji-grpc-server (in private) by @kiotaku
ゲームサーバ。主にポイント等の管理とゲームルールに即した判定を行う。
### kaiji-baccarat-client (in private) by anonymous developer
バカラ表示用クライアント。Unity使用。操作はAndroidアプリより。
### kaiji-roulette-client (in private) by anonymous developer
ルーレットクライアント。Unity使用。水平面投影向け。
### ホームページ (in private) by amedama
公式ホームページ。文化祭期間中のみ公開。

## 今年の予定
* サーマルプリンタによるQRコード会員証発行
* iOS版クライアントを作成
* サーバのクラウド化
* 来場者向けのポイント確認マシンの作成
