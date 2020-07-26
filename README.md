# bootstrapのインストール
```
$ brew install yarn
$ yarn add jquery
$ yarn add bootstrap@3
```
[app/assets/stylesheets/application.css]を[app/assets/stylesheets/application.scss]に変更
```
*= require bootstrap/dist/css/bootstrap.min
*= require_tree .
*= require_self
*/
```
[app/assets/javascript/application.js]
```
//= require rails-ujs
//= require turbolinks
//= require jquery/dist/jquery.js
//= require bootstrap/dist/js/bootstrap.min
//= require_tree .
```
# 基本

1. bootstrap3以外だとレイアウトが崩れる
1. テキストのcssは若干修正する必要がる

# ハンバーガーメニュー
https://diver.diveintocode.jp/curriculums/474

# 疑問
[views/layouts/application.html.erb]に以下の記載は必要？
```
<meta name="viewport" content="width=device-width">
```

Bootstrap2で[.gitignore]からpublic/assetsを削除する意味がわからない
