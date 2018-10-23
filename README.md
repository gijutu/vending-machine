## 動作
ruby lib/vending_machine.rb

## パス
ユーザー任意/Vending_Machine_Practice/lib/vending_machine.rb

## 自動販売機機能一覧
### 初期設定
Vender.new
### 投入口
Vender.new.slot_money
### 返却口
Vender.new.return_money
### 購入ボタン
Vender.new.purchase
### 商品一覧
Vender.new.select_view
### 取り出し口
Vender.new.pull_drink

## ユーザー操作
### お金を入れる
Vender.new.slot_money 100
### 商品を買う
Vender.new.purchase 1

## 管理者操作
### 在庫情報
Vender.new.stock_drink