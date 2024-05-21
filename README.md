#   こうかとん疾風伝

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公キャラクター

## ゲームの実装
### 共通基本機能
* 背景画像と主人公キャラクターの描画
* 主人公キャラクターがビームをでせる
* 敵が出てくる

### 担当追加機能
* こうかとんのライフゲージ追加とダメージを受けた時の影響(担当: ささき):こうかとんのライフゲージを表示,ダメージを受けた時に点滅
* レベル機能(担当:おさだ):スコアに応じてレベルが上がり敵の量も増える
* ボスの追加機能(担当:おさだ):レベルがある程度上がったらボスを出現させる
* 螺旋弾機能(担当:せきね):ビームを発生させる時、ためを作るここにより複数出せるようにする
* タイトル画面表示機能(担当:ディニー):タイトル画面を表示させる機能
* アイテム機能(担当:にた):期待してください
* ゴール機能(担当:ディニー):ゴールする機能


### ToDo


### メモ
* すべてのクラスに関係する関数は，クラスの外で定義してある
