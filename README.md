# MyDash App

## サービス概要
MyDashは自身の管理したい項目でダッシュボード（ブックマーク機能）を作成し、カスタマイズを行うことができる
管理ツールの作成サービスです。

##　想定されるユーザー層
10〜30代向けの日常的にPCを使用するユーザー
（管理ツールのため、幅広い層がターゲットではあるが、カスタマイズできるという独自性を持たせるところから若い層がメインターゲット）

## サービスコンセプト
* ユーザーが抱えている課題感と提供するサービスでどのように解決するのか
MyDashは日常的に利用するインターネットのさまざまなコンテンツ(サイトや埋め込み動画など)を柔軟に、
より自身の使いやすい形で管理することを目的として考案しました。

* なぜそのサービスを作ろうと思ったのか
サービス考案のきっかけは自身が実際の業務や日常生活において、自身に必要なインターネットの情報を
サービスの標準（例：ブックマーク機能）、またはテキストエディタなど様々な管理をしており、
使いずらさや、煩雑さ感じていました。
本来分析等で用いられるダッシュボードという形式をブックマークのように使用することができないかと思ったからです。
また複数人で作業をする際に、知識にばらつきがあり、情報レベルに差が出てしまうこともあるため、
知識共有が楽になる方法がないかと考えたことも一因です。

* どこが売りになるか、差別化ポイントになるか
・管理方法が一箇所にまとまっていること、また自身でカスタマイズすることができれば、
コンテンツの管理が容易になるのではないかと考えました。
・グループを作成することで共通のリストを使用し、情報共有が楽になる。個人のダッシュボードには 所属するグループの情報、個人用にまとめた情報の出し分けを行うことができる。
・iPhoneのようなウィジェット機能。（例：特定のユーザーの最新ツイートを常に更新して表示する。）

* どのようなサービスにしていきたいか
MyDashを使用し、少しでも自身に必要な情報の管理の効率化、自分の好きなことを留めておくことのできる
ツールにしていきたいと考えています。またブックマークバーのようなコンパクトさではなく、自身、グループのホーム画面として利用されることが目的です。


## 実装を予定している機能
### MVP
* 会員登録
* ログイン 
* パスワードリセットメール送信
* パスワードリセット
* ダッシュボード一覧
* ブックマーク 登録
  * -サイトURL
  * -動画URL
* ブックマーク 編集
* ブックマーク 削除
* ブックマークフォルダ 登録（3階層まで）
  * →ユーザーの管理のしやすさのため
* ブックマークフォルダ 編集
* ブックマークフォルダ 削除
* ブックマークカテゴリ 登録
* ブックマークカテゴリ 編集
* ブックマークカテゴリ 削除
* グループ管理
* グループ追加
* グループ編集（削除、名称変更）
* メンバー管理
* メンバー編集（削除、権限変更）
* メンバー追加
* ユーザプロフィール編集

### その後の機能
* 通知機能
* テンプレート登録機能
* 個人のブックマークの閲覧機能
* ウィジェット登録

### 画面遷移図
Figma：https://www.figma.com/design/6wkPWkMb4IXGNfZRTX1RAP/%E7%94%BB%E9%9D%A2%E8%A8%AD%E8%A8%88%E5%9B%B3?node-id=0-1&t=X3H9D3jgzMd22qtN-1

### ER図
draw.io：https://drive.google.com/file/d/1DDuNy2xXZyXmvwPK8Ml6wjUAXtKpG7Nw/view?usp=sharing
