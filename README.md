# compornent（共通部品）

## イメージ画像
<img width="413" alt="image" src="https://user-images.githubusercontent.com/99580997/161779469-2b629417-28d0-49b1-9ae8-1526c8e5d8a4.png">
<img width="778" alt="image" src="https://user-images.githubusercontent.com/99580997/161779543-8c04f739-7613-4cc4-a0f0-3327c91aca75.png">
<img width="1237" alt="image" src="https://user-images.githubusercontent.com/99580997/161779603-df3f6382-6005-42a6-8fdd-56d221e2b144.png">


## 概要

- カード（画像（アスペクト比を固定）、カテゴリ）※aspect-ratio: 4/3;
- https://www.notion.so/000_web-component-index-c4b399010bf342e9b4e2ed516cf9c730

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- `display: inline-block`、`display: block`の使い分けに注意。
- 意味なく`display: inline-block`は使わない。
- これに注意しないと画像の下に隙間ができます。

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> card をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/
- <img width="746" alt="image" src="https://user-images.githubusercontent.com/99580997/161375934-07cd84f0-d202-413b-87d4-6118eec30cd7.png">

## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/
- <img width="948" alt="image" src="https://user-images.githubusercontent.com/99580997/161375951-e498e3c0-e103-42bd-88c0-d5233e412d9c.png">

## portfolio url:

- https://c-0046.wtb.cfbx.jp/

## 参考にしたサイト

- 最新の CLS 対応は aspect-ratio がベスト！padding-top はもう古い
- https://coosy.co.jp/blog/cls-aspect-ratio/
- CSS aspect-ratio プロパティの使い方、レスポンシブやレイアウトシフトで大活躍
- https://tinyurl.com/yc59y2a7
- aspect-ratio
- https://developer.mozilla.org/ja/docs/Web/CSS/aspect-ratio

## 更新履歴

- 2022/4/5 カテゴリを擬似要素で実装
- 2022/4/5 修正完了
- 2022/4/5 再作成（アスペクト比（※aspect-ratio: 4/3;）当てるところが間違えてたので修正する。
- 2022/4/2 初版 作成完了(カード（画像（アスペクト比を固定）、カテゴリ）※aspect-ratio: 4/3;)

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
