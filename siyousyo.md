# SPAJAM2017　技術仕様書

## チーム名
- Les Miserables

## アプリ名
- チャンバランド！

## メールアドレス
- (略)

## メンバーと各担当範囲
- 河端 エンジニア、アプリ
- 蔵内 エンジニア、アプリ
- 齋藤 デザイナー
- 佐々木 エンジニア、アプリ
- 西村 エンジニア、サーバーサイド

## 仕様言語と動作環境
- サーバーサイド: Javascript
- クライアントサイド: XcodeでSwift 3 (iOS 10.3.2で動作を確認) 

## 利用しているライブラリ・ミドルウェアとその利用目的
- Node.js サーバーサイドを動かす
- socket.io ちゃんばら対戦をする二人の非同期処理

## 利用しているサービスとその利用目的
- なし

## 技術的に工夫した点・苦労した点
- ユーザー体験にこだわってより没入感を高めた
  - ex. ガードの際のバイブレーション、アクションの組み合わせ(ex. ガード x 斬り、斬り x 斬り)によって効果音を変える
- 斬りの判定、ガードの判定や各種モーションの同時を判定する時間差などをゲームが楽しくなるように調整した
  - 加速度の閾値など
