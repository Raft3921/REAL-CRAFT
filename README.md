# REAL CRAFT α 0.1

iPad・PCのブラウザで動く、REAL CRAFTの最初のプレイ可能版です。

## 入っている機能

- タイトル画面
- 「はじめから」「つづきから」
- 一人称視点
- 移動とジャンプ
- ブロック破壊・設置
- 5種類の基本ブロック
- 自動生成ワールド
- iPad用タッチ操作
- PC用キーボード・マウス操作
- セーブ・ロード
- ホットバー

## GitHubへ入れる方法

1. ZIPを展開します。
2. 展開した `REAL-CRAFT` フォルダの中身を、REAL CRAFT Uploaderで選択しているフォルダへコピーします。
3. `REAL CRAFT Uploader` を開きます。
4. 「変更を確認」を押します。
5. 「変更分だけアップロード」を押します。

## GitHub Pagesで公開する方法

GitHubの `REAL-CRAFT` リポジトリで：

1. Settings
2. Pages
3. Build and deployment を `Deploy from a branch`
4. Branchを `main`、フォルダを `/ (root)`
5. Save

しばらくすると公開URLが作られます。

## 操作

### iPad

- 左スティック：移動
- 画面右側ドラッグ：視点移動
- 跳：ジャンプ
- 破壊：見ているブロックを破壊
- 設置：選択中のブロックを設置
- 画面下のスロット：ブロック選択

### PC

- WASD：移動
- Shift：走る
- Space：ジャンプ
- マウス：視点
- 左クリック：破壊
- 右クリック：設置
- 1〜5：ブロック選択
- Esc：ポーズ

## 注意

Three.jsをCDNから読み込むため、初回起動時にはインターネット接続が必要です。
