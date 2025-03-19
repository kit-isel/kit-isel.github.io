---
title: "アプリケーション紹介"
date: 2024-10-03
---
## アプリ名
mocobo/モコボ（my own cook book/自分だけのレシピ帳）

## 仕様
### ホーム画面
①料理一覧画面、②検索画面、③設定画面を画面に表示し、一番上に表示されるものを切り替えることで画面を切り替える

### レシピ一覧画面
<img width="200" alt="レシピ一覧.jpg (142.8 kB)" src="https://img.esa.io/uploads/production/attachments/21530/2024/10/11/166465/e7c0bf03-0ea9-4fb3-9f10-b542202ed997.jpg">

作成したレシピが一覧で表示される。画面に入りきらない場合はスクロールできる。
一覧にはレシピの「料理の写真」「タイトル」「金額」「所要時間」が表示される。
各レシピの写真をタップすることで各【レシピ詳細画面】に飛ぶ。
右下の「＋」ボタンで【レシピ追加・編集画面】に飛ぶ。

### 検索画面
<img width="200" alt="検索.jpg (57.6 kB)" src="https://img.esa.io/uploads/production/attachments/21530/2024/10/11/166465/a1fb2b1c-1e90-499d-859e-8a11972ad3e5.jpg">
<img width="200" alt="検索2.jpg (79.4 kB)" src="https://img.esa.io/uploads/production/attachments/21530/2024/10/11/166465/f6b7e75f-10eb-4178-94ec-28637f3168d6.jpg">


キーワード検索：キーワードを入れるとそのキーワードがタイトルに含まれるレシピを検索することができる
範囲絞り込み：金額、所要時間で上限と下限を設定しその範囲内のレシピを検索することができる
キーワード検索と各範囲絞り込みは併用可能

### 設定画面
<img width="200" alt="設定.jpg (35.3 kB)" src="https://img.esa.io/uploads/production/attachments/21530/2024/10/11/166465/ea30e2ca-ac0d-4896-bed8-8bbb5c566435.jpg">

今後設定機能を追加した時のために画面だけ用意しておいた。今は仮の画面としてテキスト「設定画面」を画面中央に表示する。

ホーム画面（料理一覧）、検索画面、設定画面で共通の仕様
画面下部にバーを配置し、左から順に「Home」「Search」「Settings」のアイコンを配置する。
それぞれが【ホーム画面（料理一覧）】【検索画面】【設定画面】に対応し、各ページに飛べるようにする。

### レシピ詳細画面
<img width="200" alt="レシピ詳細.jpg (113.5 kB)" src="https://img.esa.io/uploads/production/attachments/21530/2024/10/11/166465/3338e250-a2a1-494f-a260-5f4d847ba9ea.jpg">
<img width="200" alt="レシピ詳細2.jpg (119.6 kB)" src="https://img.esa.io/uploads/production/attachments/21530/2024/10/11/166465/1952038f-cfea-4655-875d-1bd814adb27f.jpg">

上から順に
・料理の写真
・タイトル（必須）
・金額
・所要時間
・材料
・作り方
・メモ（味が濃かったから次は薄めなどの補足情報を書くところ）
の項目がある。

未入力の項目は表示されずに入力されている項目のみが表示される。
右上のペンのアイコンを押すと【レシピ追加・編集画面】に飛ぶ。
右上のゴミ箱のアイコンを押すとレシピを消去できる。（削除前に警告のダイアログが出る）

### レシピ追加・編集画面
<img width="200" alt="レシピ追加.jpg (47.3 kB)" src="https://img.esa.io/uploads/production/attachments/21530/2024/10/11/166465/323e2fde-5df6-4274-8ade-47fa8539fc13.jpg">
<img width="200" alt="レシピ編集.jpg (96.9 kB)" src="https://img.esa.io/uploads/production/attachments/21530/2024/10/11/166465/ea643aef-e7fe-45af-8204-26f0c90fd26a.jpg">
<img width="200" alt="レシピ編集2.jpg (112.8 kB)" src="https://img.esa.io/uploads/production/attachments/21530/2024/10/11/166465/ed2c7cb8-3c88-4234-b38d-7716fdab0b20.jpg">

料理ページの追加・編集を行う。
料理の写真はスマホのフォルダ内から選ぶことができる。
タイトルは必須で未入力のまま保存しようとすると入力を促すダイアログが出る。
保存ボタンを押すとレシピが保存される。

## クラス図
自分がわかりやすいようにクラス図を作成したので載せておきます。
ツールはPlantUMLを使用しました。
⚠️厳密にクラス図の作成ルールに則って作成したわけではなく自分なりのものなので変なところがあるかもしれません。

<img width="706" alt="スクリーンショット 2024-10-11 15.37.27.png (119.5 kB)" src="https://img.esa.io/uploads/production/attachments/21530/2024/10/11/166465/6da9414a-1f04-41ed-bb23-07fe49e17da5.png">