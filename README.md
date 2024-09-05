# business-card-template
名刺作成用のテンプレートです<br />
<br />
ブラウザの開発者ツールで画像として出力 → 編集ソフトでPDFファイルとして書き出し<br />
とすることで入稿用データに変換できます


## Google Chromeで画像ファイルとして書き出す方法
### 1. 開発者ツールを開きます
︙（ケバブメニュー） → その他のツール → デベロッパー ツール<br />
の順でクリックし、開発者ツールを開きます
<img width="1440" alt="スクリーンショット 2024-08-16 14 40 27" src="https://github.com/user-attachments/assets/1e0b488f-266d-40a3-882d-66cd179434e2">

### 2. カスタム デバイスを作成します
1. 「デバイスのツールバーを切り替え」ボタンをクリックします
<img width="1440" alt="スクリーンショット 2024-08-18 10 45 39" src="https://github.com/user-attachments/assets/e22b1950-3b55-4a0e-b19b-f29ab2080ce4">
<br /><br />
2. 「サイズ: レスポンシブ▼」 →　「編集...」 とクリックします
<img width="1440" alt="スクリーンショット 2024-08-18 10 50 16" src="https://github.com/user-attachments/assets/a30abb38-79a7-4289-b435-15737a1f7947">
<br /><br />
3. 「カスタム デバイスを追加...」ボタンをクリックします
<img width="1440" alt="スクリーンショット 2024-08-18 10 54 25" src="https://github.com/user-attachments/assets/3f838730-1eee-4890-a12f-e6b7522ff120">
<br /><br />
4. デバイス名、幅、高さ、デバイスのピクセル比を入力し、「追加」ボタンをクリックします

- デバイス名は任意の名前を入力してください<br />
（今回追加するカスタム デバイスの名前になります）
- 幅、高さも任意の値を入力してください<br />
（CSSで幅と高さを固定しているため、どんな値でも影響がありません）
- デバイスのピクセル比には上限の値を入力してください<br />
（ここの値によって撮れるスクリーンショットの解像度が変わります）
<img width="1440" alt="スクリーンショット 2024-08-18 10 57 48" src="https://github.com/user-attachments/assets/c84e29bb-cd10-451d-87ce-a4c77a308cb1">
<br /><br />
5. 「サイズ: レスポンシブ▼」 →　「（先ほど入力したデバイス名）」 とクリックします
<img width="1440" alt="スクリーンショット 2024-08-18 11 09 17" src="https://github.com/user-attachments/assets/6b480a9c-7aae-4e27-b380-569854a4364a">
<br /><br />
6. 閉じるボタンをクリックします
<img width="1440" alt="スクリーンショット 2024-08-18 11 11 10" src="https://github.com/user-attachments/assets/ad0d9c85-8a64-46f9-aa5f-8197533be772">

### 3. ノードのスクリーンショットを撮ります
「要素」タブで`<html lang="ja">`を右クリック → 「ノードのスクリーンショットをキャプチャ」をクリック<br />
とすることで名刺部分だけのスクリーンショットが撮れます
<img width="1440" alt="スクリーンショット 2024-08-18 11 12 41" src="https://github.com/user-attachments/assets/4ac49970-f72a-46f6-944b-d1776da66e22">

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
