# business-card-template
名刺作成用のテンプレートです<br />
<br />
ブラウザの開発者ツールで画像として出力 → 編集ソフトでPDFファイルとして書き出し<br />
とすることで入稿用データに変換できます


## Google Chromeで画像ファイルとして書き出す方法
### 1. 開発者ツールを開きます
ハンバーガーメニュー（縦の「・・・」） → その他のツール → デベロッパー ツール<br />
の順でクリックし、開発者ツールを開きます
<img width="1440" alt="スクリーンショット 2024-08-16 14 40 27" src="https://github.com/user-attachments/assets/1e0b488f-266d-40a3-882d-66cd179434e2">

### 2. ノードのスクリーンショットを撮ります
「要素」タブで`<html lang="ja">`を右クリック → 「ノードのスクリーンショットをキャプチャ」をクリック<br />
とすることで名刺部分だけのスクリーンショットが撮れます
<img width="1440" alt="スクリーンショット 2024-08-16 14 52 56" src="https://github.com/user-attachments/assets/0d17aa2b-c723-43cd-a995-a1e6cce742f7">

### 以上！
あとはGIMPなりペイントなりFinderなりのお好きなツールでPDFファイルに変換して入稿してください！

<br />
<br />


## Node.jsをインストール済みな人向け
`reload`というパッケージが便利だったので共有しておきます
### 実行コマンド
```🐚
npx reload -b
```
### npmのページ
https://www.npmjs.com/package/reload
