# アプリ名
# Improve_ourselves

自己の成長のために立てた目標に向かう中で、挫けそうになる瞬間があります。  
そんな時に、同じく努力を重ねている仲間の姿を励みに、切磋琢磨し合える場所を作りたいと思いました。  
このアプリは、自己研鑽に励む人達が、互いを応援し合うコミュニティを提供するものです。

# バージョン
Ruby 2.6.5  
Ruby on Rails 5.2.5

# 機能一覧
### (カッコ書きの機能は卒業後に実装予定)
* ログイン機能
* ユーザ登録機能
  * 名前、メールアドレス、パスワードは必須
* （ユーザプロフィール機能）
* コミュニティ登録機能
* （コミュニティ参加機能）
* （コミュニティ招待機能）
* コメント機能
  * コメント作成、編集、削除
  * （イイねや絵文字でリアクションを返す機能）
* （タスク作成機能）
  * 一覧、詳細、編集、削除
* （アプリ使用時間制限機能）
* （画像投稿機能）

# カタログ設計
https://docs.google.com/spreadsheets/d/1zGYtbdTL-d7dMiBC32UDvWL70ch93u1l8CcBj5s0lLU/edit?usp=sharing

# テーブル定義
https://docs.google.com/spreadsheets/d/1nvQ_AJCZ1cA0OtDtYYa7s_9D2O4ByXafl2h0uImcDAQ/edit?usp=sharing

# ER図
https://cacoo.com/diagrams/jwdtShyEXD0TW567/AD8CD

# 画面遷移図
https://cacoo.com/diagrams/Xu8ehtT5OKOaknAT/FE804

# ワイヤーフレーム
https://cacoo.com/diagrams/gmcipLpj6kCdZ9D3/B169B

# 使用予定Gem
### (カッコ書きのGemは卒業後に実装予定)
* device
* ransack
* rspec-rails
* factory_bot_rails
* capybara
* webdrivers
* (carrierwave)
* (mini_magic)

# 就業タームから使用する技術
* コメント機能（編集や削除もできること。投稿失敗時にエラーメッセージをAjaxで出力すること）
* devise

# カリキュラム外から使用する技術
* ransack