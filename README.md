# Bookers for Engineer

## サイト概要
エンジニアが自身のおすすめの技術書の情報や講評をSNS形式で気軽にシェアするアプリです。 初学者からベテランエンジニアまで技術書というものを通じて繋がり、交流を深められる手助けができるアプリになっています。

### サイトテーマ
おすすめの技術書の共有をとおして初学者からベテランエンジニアまで全ての利用者のプログラミング学習をより豊かにするためのオンラインプラットフォームです。チャットでの交流もできるため、単なるレビューの閲覧以上の繋がりが生まれます。

### テーマを選んだ理由
もともと自分自身読書好きなこと。そして、最大の理由は自分自身が初学者として勉強を始める中で、おすすめの技術書を見つけられるサービスがあったらいいのにと思ったからです。
また、昨今オンラインサロンのようにエンジニア同士のつながりを求める流れも強まっていると思うので、そのような形を作れたらと思いからこのテーマにしました。

### ターゲットユーザ
- どの技術書で勉強したらいいか知りたいプログラミング学習初学者
- エンジニア同士の交流を図りたい人
- 自分のおすすめを共有したいエンジニア


### 主な利用シーン
- 自分のおすすめの技術書を共有できます。
- 投稿にはいいねがつけられます。
- フォローしたユーザーとDMで直接やり取りができます。交流や教え合いの場になるかもしれません。

## 機能一覧・設計図
### 機能一覧
https://docs.google.com/spreadsheets/d/19kRGQ8CLUj5E8IfrRC2VRO6gvJSvg5Hwv_3ZDxYdHu4/edit?usp=sharing

### ER図
https://drive.google.com/file/d/1fVZy1-kZA-hzbWp4HrfljgxmTiMDkr3N/view?usp=sharing

### WBS
https://docs.google.com/spreadsheets/d/1UIEe3aswPfoaLeIGcCW8BCvjLjLQI04YsKqbWyDdR5Y/edit?usp=sharing

### インフラ構成図



## 環境・使用技術
### 開発環境
- OS：Linux(CentOS)
- DB : Sqlite3
- IDE：Cloud9

### フロントエンド
- Bootstrap 3.3.6
- JavaScript、jQuery、Ajax

### バックエンド
- Ruby 2.6.3
- Rails 5.2.4.4

### 本番環境
- AWS
- MySQL2
- Nginx、 Puma

### テスト
- Rspec

### その他主な使用技術
- 非同期通信 (フォロー・いいね・コメント・チャット)
- SPA

